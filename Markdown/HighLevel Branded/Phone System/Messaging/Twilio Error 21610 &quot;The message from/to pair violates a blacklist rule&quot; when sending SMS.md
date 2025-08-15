**Date Updated:** 2021-08-17T23:59:30.000Z

The Twilio API will return this message if you attempt to send an SMS or MMS to a recipient who has previously replied to your Twilio number with one of the following keywords:

  
STOP

STOPALL

UNSUBSCRIBE

CANCEL

END

QUIT

  
In this scenario, your message would not be sent, and you would not be charged for the message attempt.

  
Notice: When a user opts out of a phone number that belongs to a Messaging Service, the user is also opted out to receiving all messages sent from that particular Messaging Service.

  
In order to successfully send messages to such recipients, they must opt into your messages by texting your number with one of the following keywords:

  
START

YES
  
  
Copied from <https://support.twilio.com/hc/en-us/articles/223133627-Error-21610-The-message-From-To-pair-violates-when-sending-SMS>