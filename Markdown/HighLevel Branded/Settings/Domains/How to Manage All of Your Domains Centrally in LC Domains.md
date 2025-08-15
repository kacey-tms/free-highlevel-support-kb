**Date Updated:** 2025-08-05T01:18:38.000Z

Bring every part of your domain’s life cycle—purchase, transfer, renewal, DNS edits, and billing—under one roof with Domain Transfer-In. Instead of juggling GoDaddy, Namecheap, and separate dashboards, you can now migrate eligible domains straight into HighLevel and manage everything beside your websites, funnels, and email tools. This guide walks you through enabling the feature, completing the five-step wizard, and avoiding common pitfalls.

**TABLE OF CONTENTS**

* [What is Domain Transfer-In?](#What-is-Domain-Transfer-In?)
* [Key Benefits of Domain Transfer-In](#Key-Benefits-of-Domain-Transfer-In)
* [Enabling Prerequisites](#Enabling-Prerequisites)
* [Understanding the Five-Step Transfer Wizard](#Understanding-the-Five-Step-Transfer-Wizard)
* [Unsupported TLDs & Pricing](#Unsupported-TLDs-&-Pricing)
* [How to Setup Domain Transfer-In](#How-to-Setup-Domain-Transfer-In)
* [Frequently Asked Questions](#Frequently-Asked-Questions)
* [Next Steps](#Next-Steps)

---

# What is Domain Transfer-In?

Domain Transfer-In is HighLevel’s native migration workflow that moves a domain from an external registrar into your HighLevel account. By importing the domain’s registration and DNS records, it eliminates extra logins, centralizes renewals, and ensures seamless integration with other HighLevel products.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050912108/original/ZFndAbEHe1FEwcS5iQG9GBXAndXkXNwjhg.png?1754336803)

## Key Benefits of Domain Transfer-In

* Centralized management: one dashboard controls DNS, renewals, and billing.
* Security & uptime: full DNS visibility without registrar lock-ins or downtime.
* No lost subscription time: current expiry date carries over and gains an extra year.
* Transparent pricing: fixed fees and location mark-ups shown up-front—no surprises.
* Instant integrations: newly transferred domains auto-populate in Sites, Funnels, and Email tools.

## Enabling Prerequisites

Domain Transfer-In relies on two settings that must be switched on before you begin.

Educational description: Setting the correct flags first prevents mid-transfer errors and unnecessary support tickets.

1. Domain Purchase (Agency-wide)  
    
   * Path: Settings ▸ Company ▸ Domain Purchase → toggle ON.  
   * Grants the agency permission to register or transfer any domain.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050912089/original/ij-4aYFc3JY-TQxXp4RT8kwUeilhxae3ww.png?1754336740)  
  
1. Domain Purchase (Per Location)  
    
   * Path: Settings ▸ Domain Purchase inside each sub-account → toggle ON.
2. Domain Transfer-In (Labs flag)  
    
   * Path: Settings ▸ Labs ▸ Sub-Account Tab ▸ Domain Transfer-In → Manage → select the locations that should use the feature.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050912088/original/pT1rNi8xNx5IKH50o9Yi3spxMRqOXSRBtQ.png?1754336740)  
  
Result: Users in chosen sub-accounts now see Purchase/Transfer Domain and Transfer-In buttons on Settings ▸ Domains.

## Understanding the Five-Step Transfer Wizard

Domain Transfer-In guides you through a simple, repeatable flow.

| Step                   | What happens                                                      | Tips & requirements                                                              |
| ---------------------- | ----------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| 1 — Enter Domain       | Type a new domain or pick an already-connected external one.      | Double-check spelling; include the full TLD (.com, .org, etc.).                  |
| 2 — Eligibility Check  | HighLevel queries ICANN and the current registrar.                | Domain must be older than 60 days, unlocked, and free of outstanding disputes.   |
| 3 — Review DNS Records | Upload a DNS zone file or let the wizard auto-scan.               | Edit, add, or remove records to match production needs. (Screenshot placeholder) |
| 4 — Finalize Transfer  | Enter the authorization (EPP) code, disable DNSSEC/Whois Privacy. | Transfer fee is charged to the agency wallet here.                               |
| 5 — Approve Transfer   | Confirm the move in your current registrar’s portal or email.     | Approving promptly can cut transfer time to minutes instead of days.             |

## Unsupported TLDs & Pricing

Certain extensions aren’t available in this launch.

| Unsupported TLDs (8/2025) | Notes                                         |
| ------------------------- | --------------------------------------------- |
| .in                       | Coming soon—ICANN compliance work in progress |
| .co.uk                    | Currently limited by Nominet’s transfer rules |
| .tv                       | High registry fees; roadmap Q4-2025           |

Fees

* Base transfer cost = registrar renewal price for one year.
* Location mark-up applies if configured.
* Charge is deducted from the agency wallet at Step 4.

The wallet must have a positive balance before starting the wizard.

## How to Setup Domain Transfer-In

Educational description: Follow this checklist to migrate a domain with zero downtime.

1. Enable prerequisites (Domain Purchase + Labs flag) as shown earlier.
2. Navigate to the Domains page inside the destination sub-account.
3. Click Transfer-In on an existing external domain or Purchase/Transfer Domain ▸ Transfer Domain.
4. Complete Steps 1-5 of the wizard:  
    
   1. Enter the domain.  
   2. Pass eligibility check (unlock domain, verify >60 days old).  
   3. Upload or edit DNS; pay special attention to MX and TXT records. (Screenshot placeholder)  
   4. Provide the EPP code, disable DNSSEC/Privacy, then Confirm and Finalize.  
   5. Approve the transfer from your current registrar’s dashboard or confirmation email.
5. Wait for the “Transfer Complete” banner in HighLevel. Typical time: 5 min – 24 hr.
6. Test website and email endpoints to ensure DNS records propagated correctly.

---

## Frequently Asked Questions

Q: How long does a transfer usually take?  
 A: Anywhere from a few minutes (after manual approval) up to five calendar days if the losing registrar waits out the ICANN window.

Q: Will my website or email go down?  
 A: No, provided you replicated your existing DNS during Step 3\. Always double-check MX and SPF records.

Q: What if my EPP code is rejected?  
 A: Make sure you copied it exactly and the domain is unlocked. Generate a fresh code, then retry Step 4.

Q: Can I cancel a transfer in progress?  
 A: Up until the losing registrar releases the domain you can abort from their dashboard; afterward, you must wait 60 days before moving again.

Q: Does the extra year start today or after current expiry?  
 A: Current expiry date remains, and one full year is added on top.

Q: Are sub-domains transferred too?  
 A: Yes—sub-domain records reside in the DNS zone and migrate during Step 3.

Q: Is Whois privacy available after the move?  
 A: Yes; re-enable privacy inside HighLevel once the transfer completes.

Q: Can I transfer premium domains (.io, .app)?  
 A: Most premium TLDs are supported; pricing follows registry rules and will display before payment.
  
  
### Next Steps

1. Enable Domain Transfer-In in your sandbox sub-account and perform a test migration.
2. Verify DNS records immediately after Step 3 and again 24 hours post-transfer.
3. Update any legacy documentation or SOPs that reference external registrar logins.
4. Educate your clients on the benefits of centralized domain management in HighLevel.
  
  