**Date Updated:** 2025-06-12T17:14:41.000Z

If you or your clients are seeing SMS messages filled with strange HTML code like <div>, <span>, or other formatting tags, this guide will show you exactly why it happens and how to fix it in under a minute.
  
  
**What’s Happening?**

  
This issue usually occurs when someone copies the content from an email and pastes it into an SMS message field within a trigger, campaign, or workflow.

  
**Why is that a problem?**

  
Emails are built with HTML formatting (like bold text, links, images, etc.). When pasted into an SMS, this formatting doesn’t get removed — and instead of a nice-looking message, the recipient gets a jumbled mess of code.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048146600/original/D4Yv_HZF0w8VQOnZEO6hbkFI-i5iBekEhg.png?1749728200)

An SMS that looks like
  
  
**How to Fix It** (In Under 1 Minute)

**Follow these steps to clean up your SMS message:**

  
**Step-by-step Checklist**

1. Copy the email content you’re planning to use.
2. Open Notepad (or any plain-text editor like TextEdit on Mac).
3. Paste the content into Notepad.

**This strips out all the HTML formatting.**  

1. Copy the plain text from Notepad.
2. Paste the plain text into the SMS message field in your workflow or campaign.
3. Save your changes and run a test SMS to make sure it’s clean.
  
  
**Pro Tip**: SMS messages support plain text only. Always preview and test your SMS steps, especially if you’re reusing content from another channel like email or social posts.
  
  