**Date Updated:** 2024-02-12T21:51:38.000Z

### More Tutorials from the Community

[](https://youtu.be/7gj5ISQqDCY)<https://youtu.be/B6hs7PPaK%5FE>

<https://youtu.be/ZBYuZjjgQ%5FA>

<https://youtu.be/EIvov7clJYk>

<https://youtu.be/EayXNoAJDmE>

## **Pushing Snapshot Updates to Client Accounts**

Follow the steps below to push Snapshot updates to linked accounts:

1. Click Settings on the Agency View
2. Click Account Snapshot
3. Click the Push update to linked accounts button found on the right side of the Snapshot you wish to push out updates for  
    
![](https://cdn.filestackcontent.com/OUOgZNLrTj6Vyug5GGfy)
4. Click Ok when prompted

  
### **What happens?**

**\*Important\***

1. New Snapshot client account items ([Snapshots Overview](#) for the list of items) which were not in the Snapshot prior, thus were added by a [Refresh (update) Snapshots](https://help.gohighlevel.com/help/refresh-update-snapshots), will be added to the client account
2. **\***Any items in the client account that were created originally from the Snapshot will be updated to their state in the most updated (present) version of the Snapshot
3. Based on (2.) if you make a change to items (ex: Campaigns) in the client account and then push an update to linked accounts, it will update the items to their state in the most updated (present) version of the Snapshot, **thus deleting the changes if they are not in the most updated version of the Snapshot -- \*** **Workaround**_:_  
    
_Create a copy of the item (campaign:_ [Copying Campaigns](https://help.gohighlevel.com/help/copying-campaigns)) _originally created by the Snapshot and make the edits there. This untethers the campaign from the Snapshot thus pushing updates out to linked accounts will not touch the copy. Note that you may need to update triggers and other items in the client account to reflect the new campaign_
4. Custom Values will not be edited or deleted, meaning it is the one exception to rules 2\. & 3\. above. This is why we suggest using them ([](https://help.gohighlevel.com/help/using-custom-values-to-master-snapshots)[Using Custom Values to Master Snapshots](https://help.gohighlevel.com/en/support/solutions/articles/48001161575))
5. Client account Users and Users (set in Campaign Configurations) will not be edited or deleted
6. Other client account items that were not originally created by the Snapshot or have been added since the Snapshot was originally loaded will not be edited or deleted
7. Snapshot updates will not be pushed to client accounts created in other agency accounts. These are client accounts that may exist in other agency accounts based on a Snapshot you shared - [Share Snapshots (with other agencies)](https://help.gohighlevel.com/help/how-to-share-account-snapshots)

  
---

## **Loading a Snapshot into an Existing Clients Account**

To learn how to Load a Snapshot into an already existing account: [Load Snapshots](https://help.gohighlevel.com/help/load-snapshots)

  
**What happens?**

1. Nothing that already exists in the client account gets deleted or changed
2. All of the Snapshot items within the Snapshot simply get added to what already exists in the client account
3. If you load the same Snapshot into the same client account multiple times, the items of the Snapshot will duplicate
4. If the snapshot has more than 100 locations to process, we’ll process the first 100 locations within the first 10 mins, then the next 100 locations after 10 min, and again 100 locations after 20 mins of initial processing.

#   