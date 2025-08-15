**Date Updated:** 2025-08-07T23:50:34.000Z

Receive real-time notifications whenever a new SaaS plan is created in your HighLevel account. This webhook automatically delivers all the plan’s configuration details—features, pricing tiers, and add-ons—allowing you to streamline billing, analytics, and custom integrations without polling the API.

  
**TABLE OF CONTENTS**

* [What is the New SaaS Plan Created Webhook?](#What-is-the-New-SaaS-Plan-Created-Webhook?)
* [Key Benefits of Webhook: New SaaS Plan Created](#Key-Benefits-of-Webhook%3A-New-SaaS-Plan-Created)
* [Payload Example](#Payload-Example)
* [Security Requirements](#Security-Requirements)
* [Error Handling & Versioning](#Error-Handling-&-Versioning)
* [Developer Resources](#Developer-Resources)
* [How To Setup Webhook: New SaaS Plan Created](#How-To-Setup-Webhook%3A-New-SaaS-Plan-Created)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

  
## **What is the New SaaS Plan Created Webhook?**

  
This system-driven webhook fires instantly whenever a new SaaS plan is added through your HighLevel agency portal. Instead of repeatedly querying the GET /plans endpoint, you’ll receive a push notification with the complete plan payload—covering its metadata, included products, pricing options, and add-ons—to ensure your systems stay up to date.

  
## **Key Benefits of Webhook: New SaaS Plan Created**

  
This webhook simplifies your operations by delivering plan details automatically as soon as they’re created.

* **Automated Billing Sync:** Keeps your billing platform current with new plan offerings
* **Real-Time Analytics:** Enables immediate tracking of plan creation trends without manual data pulls
* **Seamless Integrations:** Powers custom workflows and third-party tools with up-to-the-second plan configurations
* **Reduced API Load:** Eliminates frequent polling of the GET /plans endpoint, improving performance

  
## **Payload Example**

  
Understanding the webhook structure helps you parse and process incoming data without guesswork.

```
POST /webhook/saas/agency-plans/:companyId {  "id": "plan_12345",  "name": "Professional Suite",  "saasProducts": [    { "id": "prod_abc", "name": "CRM", "enabled": true },    { "id": "prod_def", "name": "Marketing Automation", "enabled": true }  ],  "prices": [    { "interval": "monthly", "amount": 49.99 },    { "interval": "yearly", "amount": 499.99 }  ],  "addOns": [    { "id": "addon_001", "name": "Extra Users", "price": 10 }  ],  "metadata": { "createdBy": "user_789", "createdAt": "2025-08-07T12:34:56Z" } }
```

_Above: A sample payload showing plan identifiers, feature toggles, pricing tiers, and optional add-ons._

  
## **Security Requirements**

  
Protect your endpoint by validating each webhook request.

HighLevel signs webhook payloads with an HMAC SHA256 signature included in the X-HighLevel-Signature header. By verifying this signature against your secret key, you can confirm the authenticity of each notification and safeguard against tampering.

_Link:_ [_Webhook Security Best Practices_](https://help.gohighlevel.com/support/solutions/articles/155000002000-webhook-security)

  
## **Error Handling & Versioning**

  
Ensure robust processing by accounting for failures and future changes.

* **Error Codes:** Respond with HTTP 2xx for success. For non-2xx responses, HighLevel retries up to three times with exponential backoff.
* **Rate Limits:** Webhook events are rate-limited to 100 requests per minute per company.
* **Versioning:** The payload follows version v1. Future versions will increment the endpoint path (e.g., /v2/agency-plans). Always check the schemaVersion field to adapt to new formats.

  
## **Developer Resources**

  
Find complementary guides and API references to expand your integration capabilities.

* [Public API Endpoints for SaaS Configurator](https://help.gohighlevel.com/support/solutions/articles/155000005768-public-api-endpoints-for-saas-configurator)
* [Guide to SaaS Plan Creation, Sales, and Customer Onboarding](https://help.gohighlevel.com/en/support/solutions/articles/155000003670)
* [Workflow Action – Webhook](https://help.gohighlevel.com/support/solutions/articles/155000003299-workflow-action-webhook)
* [Custom Webhook – LC Premium Action](https://help.gohighlevel.com/support/solutions/articles/48001238167-guide-to-custom-webhook-workflow-action)

  
## **How To Setup Webhook: New SaaS Plan Created**

  
Proper setup ensures you receive and process new plan notifications without interruption.

1. **Enable SaaS Mode:** Confirm that SaaS mode is activated in your HighLevel agency settings.
2. **Configure Endpoint:** Create a secure HTTP endpoint in your application to handle POST requests at /webhook/saas/agency-plans/:companyId.
3. **Set Secret Key:** In the HighLevel portal, navigate to **Settings > Webhooks**, add your endpoint URL, and enter your HMAC secret.
4. **Validate Signatures:** Implement HMAC verification based on the secret. Reject requests with invalid signatures.
5. **Test Notifications:** Create a new SaaS plan in the portal and verify your endpoint receives the sample payload.

  
---

##   

## **Frequently Asked Questions**

  
**Q: How do I retrieve past plan creation events?**

A: Use the GET /plans endpoint to list historical plans; webhooks only deliver new events.

  
**Q: What happens if my endpoint returns HTTP 500?**

A: HighLevel retries delivery up to three times with exponential backoff. Ensure your endpoint handles idempotency.

  
**Q: Can I filter specific plan types from the webhook?**

A: No, this webhook fires for all plan creations. Implement filtering logic in your receiver based on metadata or plan properties.

  
**Q: Will I receive updates if a plan is modified?**

A: No. For plan updates, subscribe to the separate **Webhook: SaaS Plan Updated** event.

  
**Q: How should I handle schema changes?**

A: Check the schemaVersion field in each payload and adjust parsing logic for new versions.

##   