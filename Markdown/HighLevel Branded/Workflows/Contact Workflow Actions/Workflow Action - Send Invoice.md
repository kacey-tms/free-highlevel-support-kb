**Date Updated:** 2025-07-24T16:35:23.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Action Name](#Action-Name)
* [Action Description](#Action-Description)
* [How to Configure](#How-to-Configure)
* [Example](#Example)

##   

## Overview

The Send Invoice action allows users to automatically send invoices to contacts within a workflow. This feature streamlines the invoicing process, ensuring timely and consistent billing for products or services provided. 

  
## Action Name

Send Invoice

  
## Action Description

* Business users will be able to configure the action name, select the From User to define the sender details, and choose a template from one of the templates created inside invoices along with the payment mode.
* Users will be able to make use of the templates created inside the invoice module to define the invoice details that need to go out to the customer. Turn the feature on in Labs under sub-account settings.
* The default/custom template configured inside the invoice settings will be used automatically to send the invoice from workflows as well

  
## How to Configure

* Select the Action - Send Invoice
* Select "From User" from the list of users
* Choose the Invoice Template
* Select the Toggle for Live or Test

  
* ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155033056412/original/CwhQxewhN8UJTUIOl0hgpfh5pBMElYdbWQ.png?1726641959)
* Select the Channel (Email, SMS, or Email & SMS) for delivery of the Invoice.  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050366880/original/CZYmyKMM705UGSpay7UNqOMRUAd5gbcbtg.png?1753355116)
  
  
## Example

  
**Send an Invoice when Opportunity Status Changes**

  
**Trigger**

Opportunity Status changed - Add a trigger and select the pipeline you want to trigger this workflow for.

  
**Action**

Send Invoice - Configure the action and it will automatically send the invoice to the contact.

  
**Outcome**

* The client receives a professional and timely invoice upon project completion, streamlining the billing process.
* The agency maintains consistent invoicing practices, reducing administrative overhead and improving cash flow.
  
  