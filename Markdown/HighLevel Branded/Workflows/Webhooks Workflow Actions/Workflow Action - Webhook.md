**Date Updated:** 2025-04-09T02:44:47.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Action Name](#Action-Name)
* [Action Description](#Action-Description)
* [Action Details](#Action-Details)
* [Example](#Example)

##   

## Overview

The "Webhook" action allows you to send data to external systems via HTTP POST requests. This is particularly useful for integrating with third-party applications, automating data transfers, or triggering events in other platforms based on workflow conditions. One such example is form submissions to another platform.

  
## Action Name

Webhook

  
## Action Description

The "Webhook" action sends an HTTP POST or GET request to a specified URL, transferring data to an external application or service. This action can be used to trigger automations in third-party systems, update external databases, or send data to custom APIs. The action provides flexibility for integrating workflows with other tools.

  
## Action Details

#### Step-by-Step Guide

1. **Choose the Action Type:**  
   * Select "Webhook" from the list of available actions in the workflow builder.
2. **Name Your Action:**  
   * Enter a descriptive name for the action, such as "Send Contact Info to External CRM."
3. **Enter the Webhook URL:**  
   * Provide the URL of the external application where the data should be sent. This is typically an endpoint URL provided by third-party systems like CRMs, email marketing tools, or other APIs.
4. **Configure Payload:**  
   * Define the data that will be sent through the webhook using JSON format. You can use merge fields to dynamically pull in information like contact details, opportunity status, or custom fields. Example:  
         
   `{  "first_name": "{{contact.first_name}}",  "last_name": "{{contact.last_name}}",  "email": "{{contact.email}}",  "phone": "{{contact.phone}}",  "status": "{{contact.status}}"}`
5. **Add Headers (Optional):**  
   * If the external system requires authentication or specific headers, you can add them here. For example, you may need to include an API key or content-type header, such as:  
         * `Authorization: Bearer <API_KEY>`  
         * `Content-Type: application/json`
6. **Add Custom Data (Optional):**  
   * If you may wish to send custom data , you can add the key and the value pair in the action such as:  
         * Key : Addr  
         * Value : Address from the value picker  
   * More information about the types of data available [here](https://doc.clickup.com/8631005/d/h/87cpx-63504/fae2fc90aa49e7a)

 7\. ****Test Webhook (Optional):**

* Before finalizing, you can use testing tools like Webhook.site or Postman to verify that the data is being sent correctly to the external system.

  
## Example

  
**Scenario:** You want to sync contact data with an external CRM whenever a new contact is created.

1. **Create Workflow Trigger:**  
   * Set up a workflow trigger to initiate when a new contact is created.
2. **Add Webhook Action:**  
   * Select the "Webhook" action and name it "Sync Contact with CRM."
3. **Enter Webhook URL:**  
   * Provide the CRM’s API endpoint for contact updates, e.g., `https://api.externaltestcrm.com/contacts/create`
4. **Configure Payload:**  
   * Define the contact details to be sent in JSON format, such as {  
   ```javascript  
   "first_name": "{{contact.first_name}}",  
   "last_name": "{{contact.last_name}}",  
   "email": "{{contact.email}}",  
   "phone": "{{contact.phone}}"  
   }  
   ```  
   JavaScript  
   `  
   `
5. **Add Headers:**  
   * Include any necessary authentication details, such as:  
         * `Authorization: Bearer abc123xyz`  
         * `Content-Type: application/json`
6. **Save and Activate the Workflow:**  
   * Once the workflow is active, every time a new contact is created , their details will automatically be sent to the external CRM.

  