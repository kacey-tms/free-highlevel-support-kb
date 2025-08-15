**Date Updated:** 2025-04-09T15:30:09.000Z

Google AdWords has a feature called conversion action. This allows you to track the success of your ads and optimise them accordingly. It’s an essential tool for advertisers who want to maximise their return on investment (ROI).

  
A conversion can be a specific customer action you've defined as valuable to your business, such as an online purchase or phone call. Conversion tracking shows you what happens after a customer interacts with your ads -- whether they purchased a product, signed up for your newsletter, and called your business.

  
In this article, we will show you how to set up conversion tracking in Google AdWords action in workflows so that you can start optimising your campaigns.
  
  
---

## **Note before getting started**

1. For the most effective reporting, please make sure to set up Google Ad reporting **[[How to setup Google Ad Reporting]](https://help.gohighlevel.com/support/solutions/articles/48001219312-how-to-set-up-google-ad-reporting)**

2. Please check that you have integrated the correct MCC id and Google Id to the location and that the email associated has the highest permissions (admin).   
  
3. UTM Tracking template is added to Google Ad Account, in Account settings or campaign settings or ad level setup. (It can ONLY be present in one place)  
  
[**Troubleshoot Guide For Google Ad Reporting**](https://help.gohighlevel.com/en/support/solutions/articles/48001219996)
  
  
---

## **TABLE OF CONTENTS**

  
   * [Note before getting started ](#Note-before-getting-started%C2%A0)
* [How to set up the Google Ad Conversion Action](#How-to-set-up-the-Google-Ad-Conversion-Action)  
   * [Step 1: Head into your Google Adwords account and click on the Goals section and click on Conversions - Summary.](#Step-1%3A%C2%A0Head-into-your-Google-Adwords-account-and-click-on-the-Goals%C2%A0section-and-click%C2%A0on%C2%A0Conversions---Summary.)  
   * [Step 2: Select the Conversion Goal](#Step-2%3A-Select-the-Conversion-Goal)  
   * [Step 3: Define the Conversion settings](#Step-3%3A-Define-the-Conversion-settings)  
   * [Step 4: Give this Conversion a name](#Step-4%3A%C2%A0Give-this-Conversion-a-name)  
   * [Step 5: Select the value for your conversion ](#Step-5%3A%C2%A0Select-the-value-for-your-conversion%C2%A0)  
   * [Step 6: Setup the conversion window and attribution model ](#Step-6%3A%C2%A0Setup-the-conversion-window-and-attribution-model%C2%A0)  
   * [Step 7: Click on Save and continue](#Step-7%3A%C2%A0Click-on-Save-and-continue)  
   * [Step 8: Now let's create the Workflow in the System](#Step-8%3A%C2%A0Now-let's-create-the-Workflow-in-the-System)  
            * [Form Submission/Order Purchases/Survey Submission](#Form-Submission/Order-Purchases/Survey-Submission)  
            * [Number Pool Calling](#Number-Pool-Calling)  
            * [Chat Widget](#Chat-Widget)  
         * [Form Submission/Order Purchases/Survey Submission](#Form-Submission/Order-Purchases/Survey-Submission-1)  
         * [Number Pool Calling](#Number-Pool-Calling-2)  
         * [Chat Widget](#Chat-Widget-3)
* [Custom Mapping](#Custom-Mapping)
* [Troubleshooting⁣](#Troubleshooting%E2%81%A3)  
      * [I have set up my conversions now how do I know it's working? ⁣](#I-have-set-up-my-conversions-now-how-do-I-know-it's-working?-%E2%81%A3)  
      * [Where can I see my conversions?⁣](#Where-can-I-see-my-conversions?%E2%81%A3)  
      * [Does this work with all triggers?⁣](#Does-this-work-with-all-triggers?%E2%81%A3)  
               * [Form Submission/Order Purchases/Survey Submission](#Form-Submission/Order-Purchases/Survey-Submission-4)  
               * [Number Pool Calling](#Number-Pool-Calling-5)  
               * [Chat Widget](#Chat-Widget-6)

  
---

# **How to set up the Google Ad Conversion Action**

##   
**Step 1:** Head into your Google Adwords account and click on the **Goals** section and clickon **Conversions -** **Summary.**

  
Click the "**\+ Create Conversion Action"**

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041164841/original/_cQqoXCpv5qBZ36OKg_kIYb5SN139f4FZA.png?1738879636)

  
**OR**

  
Click on the 'Create' button on top left and select '**Conversion action**' to land on the same page as above to create a new conversion action.  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041164866/original/k52q7HfdQmUIOqP2JPmxYfew9BN3QVOwzQ.png?1738879746)  
  
  
To start tracking conversions, we need to choose the **Conversions offline** option.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041164897/original/JoSS9HE3nJ7rfZU5WcOaMYYILYJRZWbCbA.png?1738879888)
  
  
Click on **Add data source** to add an offline data source and select 'Skip this step and set up a data source later' :

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165041/original/SldhPF-SfPp1svv0pNKQlkEtTSoCX72ouQ.png?1738880326)

  
---

## **Step 2**: Select the **Conversion Goal**

  
This step is to define, "**What do you want to measure?**" > Select Converted lead:

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165163/original/P2DrbHQu4AuU8hNMxCGea8qyx7hNw2L0DQ.png?1738880512)

  
Post selection of the conversion category, you need to add an event to the category:  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165282/original/tRvUvj83JNftC_xjWgRtyWja7mSQto0pYg.png?1738880773)  

Select "**Offline data sources**":

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165293/original/9NDFAIPR10b1ZetMRpcYkibdyg_EztVdcg.png?1738880830)

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165638/original/BbxDTBAOdIWfKSzl1H2JzG0jldb5S6iotA.png?1738882209)

  
---

## **Step 3**: Define the **Conversion settings**

  
Click on '**Conversion source**' **settings** to define the details.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165308/original/WLYJ4Z-kMbgGXRlCvHOBjeRsJvnUhwL7xQ.png?1738880905)

  
This section shows the action optimisation which shows the 'Conversion Goal' selected in the earlier steps. Let the radio button be **'** **Primary action used for bidding optimisation'** as the selected choice:

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165700/original/S-tHZSX3f0eYJ6qoLJXOPiu7sp8kh2FNfA.png?1738882433)

  
---

## **Step 4:** **Give this Conversion a name**

  
Please type in the name of your conversion. In this example, we are calling it "**Conversion Test**".

  
**Note:**

Once you have completed this step please **copy and paste** your **conversion name** somewhere close. This will be used in a workflow trigger on the last step of this guide.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165761/original/X6Y1OrCepwE1jyQYEaHEL7zAtXjksoVHQw.png?1738882745)

  
---

## **Step 5:** **Select the value for your conversion** 

  
Select from: same, different, or don't use a value... **[More info](https://support.google.com/google-ads/answer/3419241?hl=en)**  

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165824/original/2_QRBo28eyhC_1u9v7rnEvv_kfdMvr2b6Q.png?1738882941)
  
  
Select the count, we recommend always **choosing option "Every"**. 

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165858/original/O6VfBuSqjx4Hf5dzrs882vG9fJMuVnwqBw.png?1738883024)

---

## **Step 6:** **Setup the conversion window and attribution model** 

  
1\. Set the _click-through conversion window_ to "**90 days"**

2\. Set the Engaged-view conversion window to google recommended, '**3 days**'

3\. Next, set the _Attribution model_ as "**Last Click**" or "**Data Driven**" (recommended).

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165949/original/44CYGHW-95_IMRs4YOoQiAyyVYS5UTsjKw.png?1738883405)

  
4\. Click on **"Done"** and the conversion settings are defined and saved.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165960/original/bSxtGy5KegHYmKATio-lg7Gv7vZGi6P2hA.png?1738883473)

  
## **Step 7:** Click on **Save and continue**

  
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165980/original/EtKIuHkSwoHKMIiZUNU3HylNeFZMNtPEKA.png?1738883584)**

  
Click on **Finish** to conclude the conversion creation process.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041165993/original/hxJ5iWFsW5BfRUTYAnAqDO8ZhxP8Num5Zw.png?1738883649)

  
---

## **Step 8:** **Now let's create the [Workflow](https://help.gohighlevel.com/en/support/solutions/articles/48001179678) in the System**

Workflow can be created for Form Submission, Order Purchases, Number Pool Calling, Survey Submission, and Chat Widget.

  
* #### [Form Submission/Order Purchases/Survey Submission](#Form-Submission/Order-Purchases/Survey-Submission)
* #### [Number Pool Calling](#Number-Pool-Calling)
* #### [Chat Widget](#Chat-Widget)

  
**Please Note:**

Every time you create a new campaign in Google, you will need to select the conversion action which you just created as your Google Adwords option in your new workflow action.   
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044787894/original/Vpe4HhgsRY1wT1ayTqa3HUhUmZaGANkSLQ.png?1744191650)

  
It will take **approximately 5 minutes** once we receive one contact with UTM source and gclid, wbraid or gbraid to get the list populated in workflow trigger as well as in Google Adwords Conversion.

###   
**Form Submission/Order Purchases/Survey Submission**

* Create the Workflow
* Select the trigger - **Form Submission, Order Form Submission,** or **Survey Submission**
* Once the trigger is selected, add the **filters** with which the Form/ Order Form/ Survey and save the trigger details
* Click on the plus icon action and select the "**A** **dd to Google Ads**" event and select the conversion action from the dropdown which was created on Google.
* Define the **Currency** and **Conversion Value** for the conversion.  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044788468/original/UaZaKAdWNot_Qk1wcZpaMLd_C7mcVfM2Wg.png?1744192040)
* Please click "Save" and "Publish" your workflow.

###   
**Number Pool Calling**

* Create the Workflow
* Select the trigger - Call Status
* Once the trigger is selected, add the filters with **Call Direction** \> **Incoming and Pool Number** \> **Select Pool Number**.
* \[Please add the pool number script on the funnel/website in header settings\]
* Click on the plus icon action and select the "**add to Google Adwords**" event and select the conversion action from the dropdown which was created on Google.
* Define the **Currency** and **Conversion Value** for the conversion.
* Please click "Save" and "Publish" your workflow.

  
### **Chat Widget**

* Create the Workflow
* Select the trigger - **Customer Replied Trigger**
* Click on the plus icon action and select the "**add to Google Adwords**" event and select the conversion action from the dropdown which was created on Google.
* Define the **Currency** and **Conversion Value** for the conversion.
* Please click "Save" and "Publish" your workflow.
  
  
---

# **Custom Mapping**

  
Previously, the system automatically mapped Google Click Identifier (GCLID), GBRAID, and WBRAID for conversion tracking. With the introduction of this new option, users can now custom map these parameters based on their specific use case.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044788285/original/2ciMoutBmiBG7b7fJ270W1p1GB-dLvK1CA.png?1744191914)  

**How It Works:**

* By default, custom mapping is disabled.
* Users can toggle it on to enable custom mapping.
* When enabled, users can map GCLID, GBRAID, and WBRAID to their own custom values.
* If custom mapping fields are provided, they will take priority over system defaults.
* If left empty, the system will continue using its default internal values.

---

# **Troubleshooting⁣**

⁣

### **I have set up my conversions now how do I know it's working? ⁣**

Currently, there is no way to test this event. You can always check your workflow action and check out the history tab⁣. It should show the execution for Google Adword Action.

⁣⁣

### **Where can I see my conversions?⁣**

It will take approximately 5 minutes to get the list populated in trigger/workflow as well as in Google AdWords Conversion. ⁣Within the 15 minutes window, you can check the workflow history.⁣  
  
### **Does this work with all triggers?⁣**

It **only works** for Form Submission, Order Purchase, Number Pool Calling, Survey Submission, and Chat Widget.

  
* #### [Form Submission/Order Purchases/Survey Submission](#Form-Submission/Order-Purchases/Survey-Submission)
* #### [Number Pool Calling](#Number-Pool-Calling)
* #### [Chat Widget](#Chat-Widget)

  