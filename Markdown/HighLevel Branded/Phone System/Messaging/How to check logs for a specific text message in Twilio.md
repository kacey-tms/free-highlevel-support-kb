**Date Updated:** 2023-05-19T15:06:28.000Z

Twilio offers several tools for investigating the interaction between Twilio and your application. If a message fails to go through, is delayed, or otherwise behaves unexpectedly, these tools should be your first stops for debugging.

---

## **How to navigate to the Messaging Logs and how to use them?**

  
You can view the error logs for your Twilio account by going to the Twilio Console. You can use this log to get an idea of which Twilio resources may be affected and who was responsible for them.
  
  
Log on to Twilio <https://console.twilio.com/>
  
  
Go to the top right -> Click Account -> Click Subaccounts  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48182954716/original/xU1ASMn2bOtT6Y1BdbfgUAYu3F-UlqKoNQ.jpeg?1643126214)
  
  
If there are too many subaccounts inside Twilio, you can go back to HL and copy the Account SIN for that location to search in Twilio:  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48243463531/original/HGHMrQLG8UVwaBtM03YuuaWZaffth7TEfg.png?1659711416)  
  
  
Now go back to Twilio with the copied Account SID

Search based on the Twilio Subaccount SID in agency level settings -> Twilio  
Paste the Account SID here and click on it:  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48182954706/original/TaZM1HBRp-VAFwRC5VUjjoQfYNndbVXXeQ.png?1643126214)
  
  
Once you are in the subaccount inside Twilio

  
Head to the Left panel, Click **Monitor** \> **Logs** \> **Messaging**  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48255066977/original/pWr2kWJpnx5K2B33Dl6aY49Oh1-RCrox1Q.png?1665005202)
  
  
Put the contact's phone number (remove all phone format) in the FROM / TO field:

  
FROM field: Contact's incoming SMS

  
TO field: Outgoing SMS

  
 Put the lead's phone number (remove all phone format) in the TO field:  

**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48282695175/original/qeVfVubDhoCFG601wHyp0zbPG9f563WZiw.png?1676914858)**  
  
  
From there, look for the message where the problem happened. Click the hyperlinked dates to go deeper into the details for each message. You’ll notice messages that don't hit a 200 are highlighted in either yellow or red.  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48256112140/original/HG-uDhFau7lI9zalH2jAjoyI1Wn1LRShEg.png?1665511651)

  
As you can see above, each log line includes the number of message segments, the message status, TO and FROM numbers, as well as if any media was attached.  
  
If it says delivered but the contact is not receiving it, grab this Message SID and [Create a support ticket with Twilio support](https://support.twilio.com/hc/en-us/articles/360048500694-Contacting-Twilio-Support) 
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48255067362/original/PkEVsPA-qqdDHczBrU2y2-69K8ibOYCgsg.png?1665005446)
  
  
In the detailed view of the message log, you can find the Message SID (Twilio's unique identifier for this message), as well as the time the resource was created, TO and FROM numbers, Delivery Steps, and the Request Inspector.
  
  
The Delivery Steps section of this log will show you when the request was created, how long it was queued on Twilio's platform, and when it was sent out to our carrier partner for delivery. These factors can help you determine where an undelivered message failed, or investigate latency issues.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48256112783/original/WKv65dNug5qnNnCBuYlnyM7Qo-0b7Qu-fg.png?1665511884)

  
The request inspector shows all requests and responses made when sending or receiving this message. You can easily see errors on requests by the color-coded status on the right of a request.  
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48256112967/original/8E4xL8VIshdTc_94LgGdLOJIcrm2tKZ_0g.png?1665511956)  
  
In the above response, we can see that we received a 404 response because Twilio was unable to find the tunnel for the webhook we set up for messages.  
  
  
If you hover over the records, it will preview the content of the message. 
  
  
How to Check if the Twilio number is MMS capable:

**1\. Go to Explore Products > Scroll down to find Phone numbers** 
  
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48160628805/original/Vy0l_oMZ3qSqcv19J62Zq1O1V1v8-FDmxQ.jpeg?1637186383)** 

  
2\. Click **Phone numbers**:

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48282696886/original/tXL3_j2jsGzytS1VG5GPGdFB5ccAgGLzlw.png?1676915376)

  
**3\. Check if the number has MMS capabilities, or if the number can send/receive SMS to domestic numbers only**

  
**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48282697269/original/zGYSm1SNWn-yD1EXaZhB4_uiMQO7xPJYMQ.png?1676915501)**  

  