**Date Updated:** 2024-08-07T17:41:37.000Z

Auto populating the existing custom field in forms / Survey using custom HTML/Javscript and later saved in submisison is simple and straightforward. 

Retrieve the Custom Field ID:

 \- Go to the Preview of the form.

 \- Right-click on the page and select 'Inspect.'

 \- Select the mouse pointer tool.

 \- Click on the "Custom Field."

 \- Copy the ID from the name and ID properties.

 **Example:** 

If you created a custom field named \`xxTrustedFormCertUrl\`, follow the above steps to get its ID.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155030589638/original/Ak0ELPT01APZudMgXz-2EIlDZnEjRjwL3A.jpeg?1723028691)

**Note:** `**myData**` **is just for example. In the customer custom HTML/Javascript code. Customer have to figure it out where is the captured data and replace the** `**myData**`

```html
document.getElementsByName('customFieldId')[0].value = myData;    
document.getElementsByName('customFieldId')[0].dispatchEvent(new Event("input"));
```

HTML