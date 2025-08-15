**Date Updated:** 2024-08-07T16:33:35.000Z

Adding additional fields through custom JavaScript is not straightforward. Customers can utilize HTML elements to add custom code for additional fields. 

  
Once the logic is implemented in the builder, the user can see these fields in the preview. However, they will not be part of the submission due to security reasons; allowing this could make the system vulnerable as any data could be passed through the submission.

  
**Workaround Solution**

If a customer adds a field called `My Own Field` using custom JavaScript/HTML and stores the input data in the `myData` variable, they need to create a holder custom field for every field added in Custom HTML/JavaScript. This holder field will act as a container for the data when changes occur in `My Own Field` .

**Steps to Implement the Solution**

  
1\. Create a Custom Field in the Builder:

 \- Ensure the custom field is created with a relevant name to act as a holder for the data from "My Own Field."

2\. Retrieve the Custom Field ID:

 \- Go to the Preview of the form.

 \- Right-click on the page and select 'Inspect.'

 \- Select the mouse pointer tool.

 \- Click on the "Custom Field."

 \- Copy the ID from the name and ID properties.

Example: If you created a custom field named \`xxTrustedFormCertUrl\`, follow the above steps to get its ID.![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155030588462/original/j1sOhpE3pKsqjvRl3aP-SvZuutfD-4ZhTw.jpeg?1723028024)

3\. Mark the Custom Field as Hidden:

There are two approach to hide the custom field in the preview

1. Native hidden feature

In the builder, mark the custom field as hidden so it won't appear in the preview. The actual `My Own Field` will still be visible.

  
 2\. Custom CSS Hidden

.menu-field-wrap:nth-child(x) { 
    display: none; 
}

here `x` in the css code stand for the element number to hide. Example if customField is 4 in the list of field the value of `x = 4` 

**NOTE: For Surveys always use Custom CSS hidden approach and for forms both works**

  
4\. Transfer Data Using JavaScript:

 \- Add the following JavaScript code to transfer the collected data from "My Own Field" to the newly created hidden custom field:
  
  
```html
document.getElementsByName('customFieldId')[0].value = myData;    
document.getElementsByName('customFieldId')[0].dispatchEvent(new Event("input"));
```

HTML

Replace \`customFieldId\` with the ID of your custom field.

By implementing this code, the data captured through `My Own Field` will be stored in the hidden custom field during the submission process.

This workaround ensures that additional fields added through custom JavaScript/HTML are securely included in the form submission.