**Date Updated:** 2025-05-10T01:57:58.000Z

This article will show you how to create professional document or contract templates — such as proposals, estimates, or service agreements — and send them automatically using workflows in HighLevel. You’ll learn how to build templates, insert custom data, trigger documents to send, and track their completion status in your CRM.

---

###   
More Tutorials From the Community

<https://www.youtube.com/watch?v=eqKz8ZFzCyY>

<https://www.youtube.com/watch?v=zcHG8DHllQI>

---

**TABLE OF CONTENTS**

* [What is the Documents & Contracts Feature?](#What-is-the-Documents-&-Contracts-Feature?)
* [Key Benefits of Sending Documents & Contracts Using Workflows](#Key-Benefits-of-Sending-Documents-&-Contracts-Using-Workflows)
* [How to Create a Document or Contract Template](#How-to-Create-a-Document-or-Contract-Template)
* [How to Send the Document Automatically via Workflow](#How-to-Send-the-Document-Automatically-via-Workflow)
* [What the Contact Receives](#What-the-Contact-Receives)
* [How to Track Document Status](#How-to-Track-Document-Status)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Related Articles](#Related-Articles)

---

# **What is the Documents & Contracts Feature?**

  
The Documents & Contracts feature lets you create branded, legally binding templates — such as proposals, estimates, or service agreements — and automatically send them through workflows based on specific triggers like a tag being added or a pipeline stage change. This automation ensures documents are delivered at the right moment in your process, eliminates manual follow-up, and helps streamline your sales or onboarding workflows.

---

## **Key Benefits of Sending Documents & Contracts Using Workflows**

  
Document automation helps streamline your service or sales pipeline while keeping interactions polished and compliant.  
  
* Send contracts automatically when specific triggers happen
* Use reusable templates with dynamic content (custom values)
* Collect legally binding e-signatures in seconds
* Include pricing/product lists directly inside the document
* Track document delivery, signing status, and completion
* Set up workflows for follow-up actions once a document is signed

---

## **How to Create a Document or Contract Template**

  
Templates are reusable and can include logos, custom values, pricing tables, and more.

####   

#### **Step 1:** Open a New Document Template  
  
* Navigate to **Payments > Documents & Contracts > Templates**.
* Click **\+ New** → _Create New Template_.
* Give your template a name (e.g., "Proposal").

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046411293/original/OmhgD7ily1z56D3MRVWiuOTi-yrf-Rx2kQ.gif?1746821717)

####   
  
**Step 2:** Design the Document Template  
  
* Use **Add Element** to build the document:
* **Image:** Upload a logo or branding element.
* **Text:** Add contract terms, service descriptions, etc.
* **Custom Values:**  Insert dynamic fields like contact name or email.
* **Product List:** Include services or items with pricing pulled from your catalog.
* **Signature Box:** Add a space for the client to sign.
* Click **Save** to store your template for future use.

_![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046411268/original/Onr7QIioElyXphNe-tZ2OJmFyiKfoag5lA.png?1746821564)_

  
Note: You can edit a saved template anytime from the Templates tab. However, changes won’t apply retroactively to documents already sent or saved as drafts.

---

## **How to Send the Document Automatically via Workflow**

  
You can automatically send a document template when a specific event happens, such as a tag being added or a pipeline stage change. To use the "Send Documents & Contracts" action, your template must be saved, and the contact must have a valid email address.

  
#### **Step 1:** Create a New Workflow

  
* Go to **Automation > Workflows**
* Click **\+ Create Workflow**, and choose _Start from Scratch_.

**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046411342/original/kJPn9QLXNOuPN69wFaCDCMItDFgTlYWFBQ.png?1746821887)**

####   
  
#### **Step 2:** Design the Workflow

  
* Select a trigger (such as Tag Added or Opportunity Updated)
* Add the **Send Documents & Contracts** action:  
    
   * Give the action a name  
   * Choose the user the document should be sent “from”  
   * Select the saved template (e.g., "Proposal")  
   * Choose whether to Send Directly or Create as Draft
* Click **Save** and then **Publish** the workflow.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046411389/original/syortgD0p_rQQ5D8m_yxUycxGRm-kq9_nQ.png?1746821997)

  
_Pro Tip:_ Use “Create as Draft” if you want to review and manually send documents later.

---

## **What the Contact Receives**

  
Once triggered, the contact receives an email with a secure link to the document.  
  
* The email includes their name and the proposal or contract details.
* They can click the link and complete the signature directly in-browser — no login or downloads required.

---

## **How to Track Document Status**

  
You can monitor whether a document is in draft, sent, viewed, or completed — all from the Documents & Contracts dashboard.

####   

* Go to **Payments > Documents & Contracts > All Documents and Contracts**.
* Use the tabs at the top to filter by:  
    
   * Drafts  
   * Waiting for Others  
   * Completed  
   * Payments

_![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046411421/original/bflqdq6OBmogTkDscLL7swmCIzriam2vA.png?1746822135)_

---

## **Frequently Asked Questions**

  
**Q: Can I edit a document after it’s sent?**  
Only if you selected “Create as Draft.” If sent directly, the document becomes locked and cannot be edited.  
  
**Q: What happens if the contact doesn’t sign?**  
The document remains in “Waiting for Others.” You can resend or manually follow up with the contact.  
  
**Q: Can I send documents to more than one person?**  
Yes, use Multiple Recipient Support to assign signature elements to multiple people in a single document.  
  
**Q: Can I collect payment when someone signs?**  
Yes. If your template includes a product list with pricing, you can enable payment collection using Stripe or another payment integration.  
  
**Q: Are signed documents legally binding?**  
Yes, HighLevel’s e-signature process complies with major digital signature regulations for legality and auditability.

  
**Q: Can recipients sign documents on mobile?**  
Yes — documents are mobile-friendly and can be signed directly from their phone’s browser.  
  
**Q: Can I preview the document before it’s sent?**  
Yes. Choose Create as Draft mode during setup to preview and manually send after final review.

---

### **Related Articles**

  
* [Workflow Action - Send Documents & Contracts](https://help.gohighlevel.com/en/support/solutions/articles/155000004887)
* [Documents & Contracts Trigger Inside Workflows](https://help.gohighlevel.com/en/support/solutions/articles/155000001491)
* [How to Use Documents & Contracts?](https://help.gohighlevel.com/en/support/solutions/articles/155000000594)
* [Customize Notifications in Documents](https://help.gohighlevel.com/en/support/solutions/articles/155000001298)
* [Automate Payments at Time of Signing](https://help.gohighlevel.com/en/support/solutions/articles/155000004504)
* [Multiple Recipient Support](https://help.gohighlevel.com/en/support/solutions/articles/155000001300)