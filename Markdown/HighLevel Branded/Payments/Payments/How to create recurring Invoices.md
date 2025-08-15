**Date Updated:** 2025-05-21T20:35:44.000Z

You may have heard of the term “recurring billing/invoicing.” It is a way for your customers to pay you automatically without having to manually enter their payment details every time they buy something from you. 

  
This can be very useful if you sell products on a subscription basis; you may want to send them an invoice every month or so for the amount due in advance. 
  
  
This article will show you how to set up and use a simple recurring invoice.

  
**Covered in this Article:**

[**What is a recurring invoice?**](#What-is-a-recurring-invoice?)

**[How to create a recurring invoice?](#How-to-create-a-recurring-invoice?)**

**[Understanding Setting invoice frequency.](#Understanding-Setting-invoice-frequency.)**

**[Status and action types in recurring templates.](#Status-and-action-types-in-recurring-templates.)**

[**View sent invoices and their payment status.**](#View-sent-invoices-and-their-payment-status.)

  
[**FAQ**](#FAQ)

[What is being shown in the list view?](#What-is-being-shown-in-the-list-view?)

[How can I get notified upon receiving payment on the invoice?](#How-can-I-get-notified-upon-receiving-payment-on-the-invoice?)

[How to stop sending future invoices?](#How-to-stop-sending-future-invoices?)

[Can I modify the price, discount, or taxes from the following occurrence?](#Can-I-modify-the-price,-discount,-or-taxes-from-the-following-occurrence?)

[Can I change the frequency setting of an ongoing recurring invoice?](#Can-I-change-the-frequency-setting-of-an-ongoing-recurring-invoice?)

[Which products can I add to recurring invoices?](#Which-products-can-I-add-to-recurring-invoices?)

---

## **What is a recurring invoice?**

A recurring invoice can be scheduled in advance to send automatically to your customers who bought a recurring service/product. You want to schedule the invoices once and forget it!  
  
  
**Please Note:**

We recommend using Stripe Connect with Invoices, in the event you do not wish to use Stripe Connect payments would need to manaully record.

##   

---

## **How to create a recurring invoice?**

* Open the "**Invoices**" tab under the payments section.
* Select "**New Recurring Invoice**" by clicking New on the All Invoices or Recurring Invoices page.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046641118/original/MHd5VV1eiCdloQ-1DHEiMcNOKoJm4rDaEQ.png?1747242276)  
  
  
## **Understanding Setting invoice frequency.**

The below table explains different cases of setting invoice frequency:  
  
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267156/original/H1XpF98s0f20CBkrSqX6aka-1Tq8P0yfHg.png?1659352474) | The first invoice will be due on July 5, 2022The second invoice will be due on July 7, 2022Invoice generation would never stop automatically                                                                                                                                                                                                                                                                                                                                                                              |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267152/original/HgQ8zTwF4h29L4hcmDVq5OCPCi0Xw446JA.png?1659352474) | The first invoice will be due on July 5, 2022The second invoice will be due on July 7, 2022The subsequent invoices would be due on the 9th, 11th, and 13th of July                                                                                                                                                                                                                                                                                                                                                        |
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267141/original/FKmBGgUtzVm6ttnQcIfecUxGBCIVsTDWxg.png?1659352471) | The first invoice will be due on July 5, 2022The second invoice will be due on July 7, 2022The subsequent invoices would be due on the 9th, and 11th of JulyNo invoice will be due on July 12                                                                                                                                                                                                                                                                                                                             |
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267140/original/ETfuisbXuHuSiE7yNVnszcr_dbuQlKpC0A.png?1659352470) | July 5, 2022, is a Tuesday for referenceThe first invoice will be due on July 18 but has to be sent two days in advance, i.e., July 16, 2022i.e.The second invoice will be due on August 1, 2022, but will be sent two days in advance, i.e., July 30, 2022\. i.e.Had July 5 been a Monday, the first invoice would be due on the same date, i.e., July 5, 2022, and would have been sent immediately. have beenThe second invoice would be due on July 19 and sent out two days in advance, i.e., July 17, 2022i.e.      |
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267159/original/75AvMs-Z_3ygcPGXbM4BS16VGoKY7ygVAQ.png?1659352475) | The first invoice will be due on September 2 and would be sent 0 days in advance, i.e., on the same date.The second invoice would be due on November 2 and sent to the customer on the same day.The scheduling will be complete after sending out three invoices to the customer as specified in the settings.                                                                                                                                                                                                            |
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267162/original/W1mFcu6UneaXhiwLDvPGozzr4vA0WfuwLQ.png?1659352475) | If, in the above example, we want to send the first invoice starting from the next month itself but at an interval of 2 months onlySimply selecting the start date as August 2 would work for the required logic.The scheduling will be complete after sending out three invoices to the customer as specified in the settings.                                                                                                                                                                                           |
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267161/original/ayPUM0Pf4vMyOO6utKd9mZ9hvrE5dKkGsA.png?1659352475) | Settings provide a solution if we want to send out the invoice to the customer on the first Monday of every month starting from the next month.The first invoice will be due on August 1 itself, given that August 1 is the first Monday in August.The invoices will be sent one day in advance.The logic also helps us end the process after the end of the year. This means the last invoice will be due on December 5, the first Monday of December.No further invoices will be due for the customer after December 5. |
| ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242267163/original/rXRhCn58nHvPbXeCdAhGIuu93IIme4RBWw.png?1659352475) | This frequency setting would allow us to send an invoice to the customer on the last date of December every year, i.e., December 31Invoice scheduling will end after sending out five invoices to the customer.                                                                                                                                                                                                                                                                                                           |

##   
  
**Status and action types in recurring templates.**

  
| **Action / Status -->** | **Draft** | **Active** | **Scheduled** | **Canceled** | **Completed** |
| ----------------------- | --------- | ---------- | ------------- | ------------ | ------------- |
| **Edit**                | Yes       | No         | No            | No           | No            |
| **View**                | No        | Yes        | Yes           | Yes          | Yes           |
| **Delete**              | Yes       | No         | Yes           | No\*         | No\*          |
| **End**                 | NA        | Yes        | Yes           | NA           | NA            |

  
**Please Note:**

**Cancelled** and **Completed** invoices can be deleted only if no invoice has been sent out to the customer. **Deleted** recurring templates are not shown in the list view.

  
---

## **View sent invoices and their payment status.**

  
Users can click on Details as shown below to know the invoices sent and their status, which will open the invoices sent and their status as shown in the right panel.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242270427/original/oLF1mEWKvJKDvlZYEtqPKWOytxZ_zJmz_w.png?1659353253)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242270428/original/03X8ytr4nvv_rGZIJo_L0EbfgKxmPDamhA.png?1659353253)  
  
  
There can be **four types** of invoices status possible here, which will also be shown in the form of tooltips above the icons:

* **Sent**: The invoice was successfully sent to the customer
* **Overdue**: The invoice was successfully sent on time but has still not been paid by the customer
* **Paid**: The customer has paid for the invoice
* **Not** Sent: There was a system error in delivering the invoice to the customer, and the invoice needs to be sent again.

  
The invoice statuses can also be checked inside the invoice builder once the recurring template is **Scheduled**, which will open the right panel similarly.  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242270429/original/DM3QvKZ0SuALY1XYbqkMvSgGu6hgmhSgew.jpeg?1659353253)

# ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242270433/original/3yHwlPeDig2vOF6FrPPy5P4v8u43zVbGOQ.jpeg?1659353254)  
  
  
---

## **FAQ**

###   
**What is being shown in the list view?**

  
The list shown on the Recurring Templates page represents the recurring templates created by the user, which are creating and sending individual invoices to the defined customer as per the frequency settings defined in them individually.

  
For simplicity, the list shows the parent invoice creator, which creates and sends out invoices per the frequency settings and customer details specified inside them. sends

###   
**How can I get notified upon receiving payment on the invoice?**

  
The table below shows the default notifications sent to the sender and receiver. The location user can create more such automation based on the invoice status(sent/paid) using invoice triggers in workflows.  
  
  
# 

| **Case**                   | **Who should receive the email?** |
| -------------------------- | --------------------------------- |
| Invoice payment successful | Receiver                          |
| Invoice payment failed     | Receiver                          |
| Invoice received           | Receiver                          |
| Invoice payment successful | Sender                            |
| Invoice payment failed     | Sender                            |

###   
**How to stop sending future invoices?**

Active or Scheduled recurring invoices can be stopped from sending out any future invoices from the Recurring Templates list page. Select the End option from the Actions dropdown and confirm the same as shown below:  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242281207/original/MDBePtgpIAd2QkVxhRXKA7bYu3ALQ-5-eg.jpeg?1659355544)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242281206/original/4BLkqrarMPKnqG_B47YM3aIQZgwKZPWMNg.jpeg?1659355544)

  
The user also has the option to end the recurring invoice from inside the invoice builder. 

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48242281204/original/NPsDsatV9n8c6_fbRfR8AK7NXu1U79iaKA.jpeg?1659355544)  
  
  
### **Can I modify the price, discount, or taxes from the following occurrence?**

No, you can't change the price, discount, or taxes after you have scheduled the recurring invoice. 

Although you can individually edit the sent-out invoice and send it over again to the customer for specific instances, there is no way to change this in automation.

  
### **Can I change the frequency setting of an ongoing recurring invoice?**

No, you can't change the frequency settings after you have scheduled the recurring invoice. 

##   

### **Which products can I add to recurring invoices?**

Only **one-time products (NOT subscriptions)** can be added to a recurring invoice. In the case of recurring products, the frequency needs to be defined inside the invoice frequency setting.  
  
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48256095836/original/cLfNMPgw-JBq8aKm_lUnetZwVJNmXq-sjQ.png?1665507242)**

---

## ****Frequently Asked Questions**

****Q: Can you cc in recurring invoices?**

At this time, **HighLevel does not offer a native option to automatically CC (carbon copy) recipients on recurring invoices** within the recurring invoice setup flow. You can specify the primary recipient (the customer), but there’s no built-in field or UI setting to CC additional email addresses on each occurrence of a recurring invoice.

****Q: Can I pause or modify a recurring invoice after it has been set up?**

**Yes, you can pause or edit a recurring invoice at any time. Simply navigate to the Recurring Invoices section, select the specific invoice, and update the schedule or details as needed.**

****Q: Will customers receive automatic reminders for unpaid recurring invoices?**

**HighLevel does not send automatic reminders for unpaid recurring invoices by default. However, you can set up automated workflows using triggers to send reminders for overdue payments.**

****Q: Can I add custom notes or terms to recurring invoices?**

**Yes, you can include custom notes or terms in recurring invoices. This is helpful for communicating important details like payment policies or personalized messages to your customers.**
  
  