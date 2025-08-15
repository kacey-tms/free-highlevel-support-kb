**Date Updated:** 2025-05-06T17:30:13.000Z

## Overview

The _Bulk Actions_ feature allows store owners to efficiently manage large sets of products from a single interface. You can now select multiple products and apply key updates across store visibility, pricing, collections, and more—saving significant time and reducing repetitive manual work.

This guide will walk you through how to use the feature, what bulk actions are available, filtering capabilities, and important edge cases to be aware of.

---

## How to Access Bulk Actions

1. Navigate to **Payments > Products** inside your Ecommerce Store.
2. Use the checkbox on each row to select individual products, or click the top checkbox to select all on the current page.
3. To select all products in the sub-account, use the **“Select All”** prompt that appears after selecting all on one page.
4. Open the **Bulk Actions** dropdown to apply your desired change.

---

## Available Bulk Actions

| Action                      | Description                                                                              |
| --------------------------- | ---------------------------------------------------------------------------------------- |
| **Update Store Visibility** | Include or exclude selected products from appearing in the online store.                 |
| **Edit Price**              | Increase, decrease, or set new prices across products using fixed values or percentages. |
| **Edit Compare-at Price**   | Same pricing options as above, applied to the 'Compare-at Price' field.                  |
| **Assign to Collections**   | Add products to one or more collections, or create new collections on the fly.           |
| **Delete Products**         | Remove selected products in bulk, with a safety confirmation modal.                      |

> ⚠️ _Note: Price updates affect all variants of the selected product._

---

## Filtering Products for Bulk Actions

Use the filtering panel to narrow down product selection before applying bulk actions. Available filters include:

* **Store Visibility** – Included / Hidden
* **Collections** – By name
* **Source** – All Products, Woocommerce

---

## ⚠️ Edge Cases & Important Notes

### Behaviour & Limitations:

* **Negative Value Protection**: Price changes that would lead to a negative value will be skipped for those products. Others will still update.
* **One Action at a Time**: You must wait for the current bulk operation to complete before starting a new one.
* **Global Store Visibility**: Visibility changes apply across all connected stores. To exclude a specific store, use the **Sites** section instead _(Sites > Stores > Select a Store > Products)_.
* **Value Required for Price Updates**: ‘Increase’ or ‘Decrease’ actions require an existing value for Price or Compare-at Price. Products without a base value remain unaffected.
* **Deletion Confirmation for Large Sets**: Deleting more than 50 products requires typing **“Delete”** in the confirmation prompt. Deleted products cannot be recovered.
* **Bulk Performance Warning**: Changes on over 300 products may take a few moments to reflect.

### Selection Behaviour:

| Action                           | What Happens                                                  |
| -------------------------------- | ------------------------------------------------------------- |
| Click top checkbox               | Selects all products on the current page.                     |
| Navigate away and return         | Selection is retained (for current page selection only).      |
| Use “Select All” for entire list | If you navigate away, the selection will **not** be retained. |

---

## FAQs

**Q: Can I apply bulk actions to digital and physical products together?**  
Yes, the action applies regardless of delivery type.

**Q: Will bulk updates affect variants?**  
Yes. All pricing-related changes will reflect at the variant level as well.

**Q: Can I undo a bulk delete?**  
No. Deleted products are **permanently removed**. Use with caution.

---

## Pro Tips

* Use filters to isolate a group before performing actions—it reduces the risk of editing the wrong products.
* Always double-check the product count and details before confirming destructive actions like delete.
* Combine filters + Select All for more targeted bulk operations.
  
  
## Images

Select Products to apply bulk actions:

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046183007/original/rJRJknlDKpQ_rOA7kJn3sQX41f2ah2WsUQ.jpeg?1746532760)

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046183000/original/lPZz-cCGTyORNLE3JAir3z6kB7q9WJ_Ffw.jpeg?1746532759)

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046183001/original/nhYkKzJn264TS--3ZQkx_zOdanDgPN5v1w.jpeg?1746532759)

Assign Collections:

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046182999/original/Z22x6R6w29sNICnrevziTMqxpinklwtEfQ.jpeg?1746532759)

Change Price:

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046183003/original/i3iEn4TRxhTV2J9VHCZJ7ik9RC4PjsKaYQ.jpeg?1746532759)

Filters:

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046183004/original/wMtOuWJEEKRr19cjO5OIm_NC3tcILotkUg.jpeg?1746532760)

Bulk Delete:

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046183002/original/5wOrxGyOTps_L0cBu3smcQ1xsNhxeyjcOg.jpeg?1746532759)

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155046182997/original/6YtDWJf1KjeoJj9eECEGGeTTX37ahs1zUg.jpeg?1746532759)

  