**Date Updated:** 2025-06-19T20:16:04.000Z

This article covers the latest updates to the HighLevel LC WordPress Plugin, including new controls for chat widget management, dropdown support for multiple widgets, SEO enhancements for Funnels, and critical backend improvements.

**TABLE OF CONTENTS**

* [What is the LC WordPress Plugin?](#What-is-the-LC-WordPress-Plugin?)
* [Key Benefits of the Wordpress LC Plugin](#Key-Benefits-of-the-Wordpress-LC-Plugin)
* [How to Enable and Manage Chat Widgets in WordPress](#How-to-Enable-and-Manage-Chat-Widgets-in-WordPress)
* [SEO Meta Tags Re-enabled in Funnels](#SEO-Meta-Tags-Re-enabled-in-Funnels)
* [Plugin Usage Tracking with Pendo](#Plugin-Usage-Tracking-with-Pendo)
* [Backend Improvements & Bug Fixes](#Backend-Improvements-&-Bug-Fixes)
* [Frequently Asked Questions](#Frequently-Asked-Questions)

---

# What is the LC WordPress Plugin?

The LC WordPress Plugin allows you to embed and manage key HighLevel functionalities directly within your WordPress site. This integration simplifies how you control live chat experiences, lead funnels, and event tracking—eliminating the need to switch platforms or manually manage embed codes.

# Key Benefits of the Wordpress LC Plugin

This release introduces new controls for chat widget activation, support for multiple widgets, and foundational improvements for better performance and analytics.

* Enable/disable chat widgets directly within the WordPress admin.
* Dropdown selector allows choosing from multiple chat widgets (one active at a time).
* Auto-sync of selected widget with the GHL Dashboard ensures consistency.
* SEO meta tags for Funnels re-enabled for enhanced search engine visibility.
* Pendo event tracking added to monitor plugin usage behavior.
* Backend stability improvements, including scheduled task (cron) reliability.

# How to Enable and Manage Chat Widgets in WordPress

You can now easily control chat widget visibility and behavior from the LC Plugin settings—without needing to copy-paste embed codes or access the GHL dashboard each time.

### Steps to Enable and Configure:

1. In your WordPress dashboard, navigate to LC Plugin > Settings.
2. Toggle the Chat Widget Enable switch to turn the widget on or off.
3. If toggled ON, a dropdown menu will appear listing all available chat widgets.
4. Select one widget from the dropdown. Only one widget can be active at a time.
5. The plugin will fetch and embed the selected widget’s configuration.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048560648/original/yGlfY2x5O7xkjXhgCa52Mbwqmj5lP4DYWA.png?1750344254)

Resolved Issue:  
Previously, widgets selected in the GHL Dashboard would not always update on the site. This issue is now fixed. The plugin now always reflects the current selection and changes from the dashboard.

# SEO Meta Tags Re-enabled in Funnels

Meta tags help improve the visibility of your Funnel pages in search engine results. With this update, HighLevel has re-enabled support for SEO tags on Funnel pages.

### Benefits:

* Funnel pages now include <title>, <meta name="description">, and other key tags.
* Enhanced discoverability and click-through rates from search engines.
* No manual reconfiguration needed—just ensure SEO settings are enabled within your Funnel setup.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155048560647/original/5p95qE16Gj1jUb3FpHzA3Nsw9ZTsPw0rdw.png?1750344254)

# Plugin Usage Tracking with Pendo

To better understand how users interact with the plugin, Pendo event tracking has been added.

### What’s Tracked:

* User interactions within the LC Plugin interface.
* Usage data for toggles, dropdowns, and plugin engagement.

Note: This data is used by HighLevel teams to refine the product and is not currently user-accessible.

# Backend Improvements & Bug Fixes

A range of behind-the-scenes upgrades make the plugin more robust and scalable.

* Authentication Cron Fix: Scheduled tasks (such as widget syncing) now run reliably.
* Plugin Architecture Refactor: Simplified and optimized the internal structure to support future enhancements and ease of maintenance.

These updates enhance performance and reduce the chances of bugs or failed updates.

---

# Frequently Asked Questions

Q: Can I activate more than one chat widget at a time?  
 No. Only one widget can be selected and embedded at a time.

Q: Will my site reflect updates made to the selected widget in the HighLevel dashboard?  
 Yes. The widget configuration is now reliably synced whenever changed in the dashboard.

Q: Do I need to manually re-enable SEO tags in Funnels?  
 No. The functionality is automatically restored. Ensure Funnel SEO settings are correctly configured.

Q: Is Pendo tracking optional?  
 No. It runs silently in the background and doesn’t affect site performance or require user configuration.

Q: Do these updates affect older versions of the plugin?  
 It’s recommended to update to the latest version to benefit from these enhancements.

#   

Next Steps

* Update your LC Plugin to the latest version from the WordPress admin.
* Enable and select your chat widget through the new toggle and dropdown.
* Review Funnel SEO settings for increased traffic opportunities.
* Keep an eye on plugin functionality to benefit from real-time updates and fixes.
* Contact support if you experience any issues with widget visibility or configuration syncing.