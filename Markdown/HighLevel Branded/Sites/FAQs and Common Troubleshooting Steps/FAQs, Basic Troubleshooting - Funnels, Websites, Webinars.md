**Date Updated:** 2025-05-07T15:08:19.000Z

## Overview

This article provides troubleshooting steps for common issues encountered while using certain features within funnels, websites, webinars. These steps will help users resolve problems related to tracking codes, custom fields, images, rendering issues, and more.

---

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Common Issues and Troubleshooting Steps](#Common-Issues-and-Troubleshooting-Steps)  
   * [1\. Head Tracking Code is Not Part of Tag](#1.-Head-Tracking-Code-is-Not-Part-of%C2%A0%3Chead%3E%C2%A0Tag)  
         * [Issue](#Issue)  
         * [Explanation](#Explanation)  
         * [Troubleshooting Steps](#Troubleshooting-Steps)  
   * [2\. Updated Custom Fields Do Not Render in Preview/Site](#2.-Updated-Custom-Fields-Do-Not-Render-in-Preview/Site)  
         * [Issue](#Issue-1)  
         * [Explanation](#Explanation-2)  
         * [Troubleshooting Steps](#Troubleshooting-Steps-3)  
   * [3\. Blurry or Slow-Loading Images](#3.-Blurry-or-Slow-Loading-Images)  
         * [Issue](#Issue-4)  
         * [Explanation](#Explanation-5)  
         * [Troubleshooting Steps](#Troubleshooting-Steps-6)  
   * [4\. Custom Values Breaking or Not Rendering in Preview](#4.-Custom-Values-Breaking-or-Not-Rendering-in-Preview)  
         * [Issue](#Issue-7)  
         * [Possible Causes & Fixes](#Possible-Causes-&-Fixes)  
   * [5\. Identifying the Funnel, Page, or Location of a Live Site](#5.-Identifying-the-Funnel,-Page,-or-Location-of-a-Live-Site)  
         * [Steps to Identify](#Steps-to-Identify)  
   * [6\. Site Not Rendering Correctly (Alignment Issues, Refresh Loops, etc.)](#6.-Site-Not-Rendering-Correctly-%28Alignment-Issues,-Refresh-Loops,-etc.%29)  
         * [Issue](#Issue-8)  
         * [Troubleshooting Steps](#Troubleshooting-Steps-9)  
   * [7\. Page Speed Score or Speed is Too Slow](#7.-Page-Speed-Score-or-Speed-is-Too-Slow)  
         * [Issue](#Issue-10)  
         * [Recommended Tools](#Recommended-Tools)  
         * [Troubleshooting & Optimization Steps](#Troubleshooting-&-Optimization-Steps)  
         * [Benchmark](#Benchmark)  
   * [8\. Site or site owner verification failing from google, meta pixel when meta tag is placed in head or head tracking code](#8.-Site-or-site-owner-verification-failing-from-google,-meta-pixel-when-meta-tag-is-placed-in-head-or-head-tracking-code)

---

## Common Issues and Troubleshooting Steps

### 1\. Head Tracking Code is Not Part of <head> Tag

#### Issue

The head and body tracking codes are injected on the client side (browser), so they won't appear inside the <head> tag in the source code. What you see in the page source is the initial HTML data used for rendering the page. Our platform dynamically injects the tracking codes on the client side, which means they will not be present in the static source view.

Even if users implement custom tracking solutions, such as Google Tag Manager (GTM), those scripts will still function as expected; client-side injection is compatible with GTM and similar tools.

#### Explanation

What you see in the source code is the page data used for rendering the page, not the dynamically injected tracking codes.

#### Troubleshooting Steps

* Refer to the video explanation for how GoHighLevel injects head and body tracking codes:[ Video Link](https://www.loom.com/share/3981c5399f2542edabebe04af3db0717)

---

### 2\. Updated Custom Fields Do Not Render in Preview/Site

#### Issue

Custom field values do not show up on the site when updated via backend (e.g., automations, workflows).

#### Explanation

* Custom fields are stored in the contact database, but the site fetches field data from local storage or cookies to render it on the next page.
* When a contact fills out a form, survey, or order form, the inputted data is saved to local storage. However, if custom field values like estimated costs are updated on the backend without direct user input, they aren't saved in local storage and therefore won’t appear on the rendered page.

#### Troubleshooting Steps

* This issue typically results in blank custom values because the necessary data isn't available in local storage for frontend rendering.
* A viable solution is to include the relevant custom fields (e.g., estimated costs) directly in the form or survey. When a user fills out these fields, the values are captured and stored in local storage.
* These values will then persist across pages and display as expected on subsequent screens.
* This behavior is by design to ensure that frontend rendering relies on locally stored data for speed and personalization.

---

### 3\. Blurry or Slow-Loading Images

#### Issue

Some images appear blurry or load slowly due to image optimization settings.

#### Explanation

* Image optimization improves page speed but applies a universal quality setting.
* Some images may lose clarity if optimization is too aggressive.

#### Troubleshooting Steps

* Disable image optimization for specific images in the builder.
* For background images, disable optimization in funnel settings.
* Upload higher-resolution images to maintain clarity after optimization.

---

### 4\. Custom Values Breaking or Not Rendering in Preview

#### Issue

Custom values do not render properly in the funnel.

#### Possible Causes & Fixes

1. Hyperlink Issue:  
   * Check if any custom value in a text element has been converted into a hyperlink.  
   * Remove hyperlinks from affected elements, as they break rendering.
2. ChatGPT Response Formatting Issue:  
   * ChatGPT-generated content may contain special characters (e.g., \\n) that break the funnel page.  
   * Update the ChatGPT prompt to return HTML-formatted content.  
   * Alternatively, use the "text formatter" action to replace \\n with <br/>.

---

### 5\. Identifying the Funnel, Page, or Location of a Live Site

#### Steps to Identify

1. Open the Network tab in the browser.
2. Clear the console and enable the XHR filter.
3. Reload the page.
4. Check the event call in the network logs.
5. Open the payload section to find the required details.

---

### 6\. Site Not Rendering Correctly (Alignment Issues, Refresh Loops, etc.)

#### Issue

The site is not displaying properly, with elements misaligned or the page continuously refreshing.

#### Troubleshooting Steps

1. Remove all custom code in code elements, head/footer tracking code, and custom CSS.  
   * To find custom code elements:  
         * Open the builder.  
         * Inspect the page preview.  
         * Use Ctrl + F (Windows) or Cmd + F (Mac) to search for c-custom-code.  
         * If found, remove custom code elements and check if the issue persists.
2. Check for Specific Issues:  
   * Ensure no sections, columns, or elements have the sticky option enabled (sticky CSS only works in preview mode).  
   * Remove expired timer elements, as they may cause display issues.  
   * Open the browser console and check for errors.  
   * If a hydration error appears, escalate the issue as a support ticket.

---

### 7\. Page Speed Score or Speed is Too Slow

#### Issue

The page is loading slowly, or speed analysis tools return low performance scores.

Note  
The dev team does not provide debugging support for improving page speed directly.

#### Recommended Tools

* [PageSpeed Insights](https://pagespeed.web.dev/)
* [GTMetrix ](https://gtmetrix.com/)

These tools help analyze the performance of a page and suggest improvements.

#### Troubleshooting & Optimization Steps

* Check for external scripts or CSS loading via tracking code or custom code elements.
* Evaluate the length and content density of the page.
* Optimize images using GoHighLevel’s image optimization toggle, or manually compress them.  
   * Best practice: Images loading above the fold should be under 200kb to help achieve good LCP scores on mobile.
* Enable "Optimize JavaScript" toggle to delay hydration of non-essential JS and tracking codes—this improves TBT (Total Blocking Time).
* Look for custom code elements injecting third-party widgets or JavaScript.
* Move heavy elements (forms, calendars, review widgets, maps, etc.) below the fold.

#### Benchmark

A well-optimized GoHighLevel page typically scores:

* Above 80 on mobile
* Above 95 on desktop.

This includes scenarios where tracking codes and high-resolution images are present.

---
  
  