**Date Updated:** 2024-09-24T01:49:29.000Z
  
  
**TABLE OF CONTENTS**

* [SMS Restriction History](#SMS-Restriction-History)
* [Enhancements](#Enhancements)
* [Bug Fixes](#Bug-Fixes)

## **SMS Restriction History**

It helps you note and track any adverse action on their SMS sending, like 

* Daily/Weekly sending limit violations
* Warning Emails and Temporary restrictions based on 30007 and opt-out rate.

This option can be found under Location > Settings > Phone numbers > Advanced settings > Restriction history

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155033404708/original/vB9fdFeisZzvyGXUZobMpnICMXob8OCXng.png?1727122597)

  
## **Enhancements**

* Number purchase flow > Search now supports blankspace and special characters as US based customers commonly use in their format
* Earlier, if you called someone belonging to a location that was disabled, the call would get disconnected without any feedback. Now you will hear a voice describing the issue and the solution along with a tooltip on the UI
* Recordings and transcriptions should now appear faster
* We were already blocking certain keywords in SMS like 'cannabis'. We will now also block 'fireworks' and 'THC'

## **Bug Fixes**

* SMS limit would sometimes not level up for users (ramp up model). This should now level up as expected
* 'PR' (Puerto Rico) now shows up as a US state instead of a country for the A2P flow
* After a sub-account transfer from one agency to another, the previous agency would get billed mistakenly. We have now fixed this issue