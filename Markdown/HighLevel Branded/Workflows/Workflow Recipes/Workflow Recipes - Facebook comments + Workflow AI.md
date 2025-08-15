**Date Updated:** 2025-04-09T02:53:32.000Z

Create a workflow from this recipe to get an example of an AI-customized reply comment that also sends a DM only if the comment was positive.

1. Trigger: fires on any first level comment in the post.
2. Action: send the comment to OpenAI with a short prompt asking for a good response.
3. Action: reply in comments with the AI response.
4. Action: send the original comment to OpenAI for a sentiment analysis and split the workflow by positive or negative.
5. Action: when positive, send an interactive DM.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155041915247/original/yZ3qAcufb-Q9EHkjkPiZP8b-RmpoN_mTWQ.png?1740011022)