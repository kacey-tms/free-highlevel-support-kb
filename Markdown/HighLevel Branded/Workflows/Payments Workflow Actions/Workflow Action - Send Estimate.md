**Date Updated:** 2025-07-24T16:38:16.000Z

**TABLE OF CONTENTS**

* [Overview](#%E2%80%8B%E2%80%8BOverview)
* [Action Name](#Action-Name)[](#Action-Description)
* [Action Description](#Action-Description)  
   * [Action Details](#Action-Details)  
   * [Example: Home Renovation Estimate](#Example%3A-Home-Renovation-Estimate)

## Overview

The **Send Estimate** action makes it easy to send personalized estimates to your customers automatically whenever specific events occur like creation of opportunities or movement from one stage to other.  
  
## Action Name

**Send Estimate**

  
## Action Description

This action enables the workflow to send a customized estimate using a template to a customer upon the occurrence of a specified trigger. Users can select templates and designate the estimate mode as live or test.  
  
### Action Details

| Value Name        | Description                                                                  | Mandatory |
| ----------------- | ---------------------------------------------------------------------------- | --------- |
| Action Name       | Descriptive name for the action.                                             | Yes       |
| From User         | The user responsible for sending the estimate.                               | Yes       |
| Estimate Template | The template used to format the estimate content.                            | Yes       |
| Estimate Mode     | Choose **Live** for actual estimates or **Test** for trials.                 | Yes       |
| Channel           | Select the Channel (Email, SMS, or Email & SMS) for delivery of the Estimate | Yes       |

###   
Example: Home Renovation Estimate

**Scenario**: A home renovation company wants to send estimates promptly when a potential client shows interest.

**Setup**:

* **Trigger**: Opportunity Created (or any other relevant trigger)
* **Action Name**: Send Home Renovation Estimate
* **From User**: Sarah Johnson
* **Estimate Template**: Home Renovation Proposal
* **Estimate Mode**: Live

**Outcome**: When the specified trigger occurs, the selected estimate is automatically sent to the customer, improving conversion potential.  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155034113607/original/t-ZV3jR2yvaDxyuur_qv8JYt8i1eSatMbA.png?1728048751)  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050367082/original/f09SLq6HtUnnuViB4YkoA1H5EM_WcBeUSA.png?1753355281)