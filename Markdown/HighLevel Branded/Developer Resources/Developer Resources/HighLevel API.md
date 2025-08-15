**Date Updated:** 2024-02-22T00:47:50.000Z

## **About Our Developer Documentation**

HighLevel is currently in the process of moving to an OAuth 2.0-based API (API 2.0), and at some point in the future, this will be the only API available for integration once this migration is complete. Until this time, we have two APIs, which we are calling the [API 1.0](https://public-api.gohighlevel.com/) and the [API 2.0](https://highlevel.stoplight.io/docs/integrations/0443d7d1a4bd0-overview) for added clarity when referencing which API you are utilizing. See further details below.

  
**API 1.0 Docs**  
**<https://public-api.gohighlevel.com/>**

* No new endpoints are planned for the Public API at this time.
* "Public API (v1)" has been renamed to API 1.0 for clarity.

  
**API 2.0 Docs**

[](https://highlevel.stoplight.io/)**<https://highlevel.stoplight.io/docs/integrations/0443d7d1a4bd0-overview>**

* Going forward, be sure to use the API 2.0 Docs for new integrations as all future endpoints and new API functionality will be added here.
* As of now, not all endpoints from the API 1.0 Docs have been integrated into the API 2.0 Docs.
* Pro Tip: To ensure an uninterrupted API integration, be sure to regularly review and update your integration as soon as a new endpoint becomes available in the API 2.0 Docs.
* "OAuth 2.0 API (v2)"has been renamed to API 2.0 for clarity.

  
**Check out our** [**Developers Landing Page**](https://developers.gohighlevel.com/), where you can find the Developer Marketplace, Documentation, Slack Channel, and more! --> <https://developers.gohighlevel.com/> [](https://developers.gohighlevel.com/)**[](https://developers.gohighlevel.com/)**

---

**TABLE OF CONTENTS**
  
  
#### [**How to Get Help or Support for the HighLevel API**](#How-to-Get-Help-or-Support-for-the-HighLevel-API)

#### **[How to Submit a New API-Related Idea to HighLevel](#How-to-Submit-a-New-API-Related-Idea-to-HighLevel)**

#### **[Differences Between API Access Across Plan Levels](#Differences-Between-API-Access-Across-Plan-Levels)**

#### [**What is an API Key and how is it used?**](#What-is-an-API-Key-and-how-is-it-used?)

**[What are the API Rate Limits for API 1.0 & 2.0?](#What-are-the-Rate-Limits-for-API-1.0-&-API-2.0?)**

####   
[**Where To Find The Agency & Location API Keys**](#Where-To-Find-The-Agency-&-Location-API-Keys)

#### [1\. Location Level > Settings > Business Info](#1.%C2%A0Location-Level-%3E-Settings%C2%A0%3E-Business-Info)

#### [2\. Agency Level > Agency Settings > API Keys to view all Location API keys in one place](#2.%C2%A0Agency-Level-%3E%C2%A0Agency-Settings-%3E-API-Keys-to-view-all-Location-API-keys-in-one-place)

####   
[**Troubleshooting**](#Troubleshooting)

   * #### [How to Update your API Keys](#How-to-Update-your-API-Keys)
   * #### [How do I know if my API Key is old?](#How-do-I-know-if-my-API-Key-is-old?)
   * #### [What will happen if my API key is compromised?](#What-will-happen-if-my-API-key-is-compromised?)
   * #### [What do I do if my API key is blank?](#What-do-I-do-if-my-API-key-is-blank?)

  
---

## **How to Get Help or Support for the HighLevel API**

  
At this time, HighLevel Support does **NOT** provide setup code auditing or developer consultative services on API-Related topics. However, if your setup is complete and correct - yet an error persists, you may have encountered an API Bug we need to fix.   
  
You can report this bug by filling out this form: [](https://speakwith.us/dev-ticket)<https://developers.gohighlevel.com/support>

  
* For any questions relating to the HighLevel API, join the developer Slack group to ask our community of talented customers here: [](https://join.slack.com/t/ghl-developer-council/shared%5Finvite/zt-puqvvhdu-lpgk5YaijZfe9XT%5Fb1LEpg)<https://www.gohighlevel.com/dev-slack>

  
* HighLevel Devs host a monthly a Developer Council Call on the second to last Friday, which you can find on the events calendar here: <https://www.gohighlevel.com/events>
  
  
## **How to Submit a New API-Related Idea to HighLevel**

Our API Docs list all available endpoints that are publicly available. If you don’t see an endpoint on either of the API developer sites listed below, we recommend visiting our [**Roadmap & Ideas Board** ](https://ideas.gohighlevel.com/integrations)to add your idea!   
  
You can also track the progress of new ideas as they make their way through planning and into production on our roadmap. This board is both for new developer features and consumer features alike.

  
###   
  
## **Differences Between API Access Across Plan Levels**

  
Basic API access is included with our Starter and Unlimited plans, while Advanced API access is available on our Agency Pro plan. 

  
In addition to the future endpoints that will be released in our OAuth 2.0 API (which is only available in our Advanced API access), this tier unlocks the use of Agency API Keys where lower plan levels only access Location API Keys. 

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48227025193/original/qVjiLkUumrEo5aDB8Cjz8gbaVT_Y2E8mFg.jpg?1652973498)  
  
  
## **What is an API Key and how is it used?**

An application programming interface key (API key) is a unique identifier used to authenticate a user, developer, or data passed via API. It's essentially a secret Key that you want to keep close and not share.

  
An authorized API key will allow you to pass data between software automatically using applications like Zapier, Pabbly, Integrately, Make (Formerly Integromat), API Nation, and others.
  
  
---

## **Where To Find The Agency & Location API Keys**

Where to find the Location Level API Key?

  
### _**1\.** **Location Level** \> **Settings** \> **Business Info**_

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48231545965/original/v7ImipA4nl8A8guw8ytaSEMwo86JNVgvWA.gif?1654791058)

  
###   
_**2\.** **Agency Level** \> **Agency Settings** \> **API Keys to view all Location API keys in one place**_

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48231543793/original/fECfr7I0Bqgu2mzbfhFVoqGsEqOBeEmNDg.gif?1654790715)

  
## **What are the Rate Limits for API 1.0 & API 2.0?**

  
**Our current rate limits for API 1.0 are:**

For Burst Requests - 100/10 seconds

For Daily - 200,000/Day

  
**Our current rate limits for API 2.0 are:**

GHL has implemented rate limits on our public V2 APIs using OAuth to ensure optimal performance and stability. These limits have been adjusted to:

  
**Burst limit:** A maximum of 100 API requests per 10 seconds for each Marketplace app (i.e., client) per resource (i.e., Location or Company).

**Daily limit:** 200,000 API requests per day for each Marketplace app (i.e., client) per resource (i.e., Location or Company).

These new limits contribute to better overall performance and stability of our system.

  
To monitor your limited usage, refer to the following **API response headers:**

  
'X-RateLimit-Limit-Daily': Your daily limit

'X-RateLimit-Daily-Remaining': The remaining number of requests for the day

'X-RateLimit-Interval-Milliseconds': The time interval for burst requests

'X-RateLimit-Max': The maximum request limit in the specified time interval

'X-RateLimit-Remaining': The remaining number of requests in the current time interval

  
---

# [**Troubleshooting**](https://help.gohighlevel.com/support/solutions/articles/48001205369-how-to-update-your-api-keys#Troubleshooting)

### [How to Update your API Keys](https://help.gohighlevel.com/support/solutions/articles/48001205369-how-to-update-your-api-keys#Updating-your-API-Keys)

### [How do I know if my API Key is old?](https://help.gohighlevel.com/support/solutions/articles/48001205369-how-to-update-your-api-keys#Q3%3A-How-do-I-know-if-my-API-Key-is-old?)

### [What will happen if my API key is compromised?](https://help.gohighlevel.com/support/solutions/articles/48001205369-how-to-update-your-api-keys#Q4%3A-What-will-happen-if-my-API-key-is-compromised?)

### [What do I do if my API key is Undefined?](https://help.gohighlevel.com/support/solutions/articles/48001205369-how-to-update-your-api-keys#Q5%3A-What-do-I-do-if-my-API-key-is-blank?)
  
  