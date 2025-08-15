**Date Updated:** 2024-08-13T11:33:56.000Z

  
Coupons support both **one-time and recurring products including main and bump products in [V2 Funnels](https://help.gohighlevel.com/en/support/solutions/articles/48001204903).**  
  
Applied coupon codes are not applicable on one-click upsells

  
Coupons are great for enticing sales! In this article, we’ll break down the basics of coupons so you know how to get the most out of them.

  
---

#### **Covered in this article:**

#### [**How to create and add coupons to products (video)**](#How-to-create-and-add-coupons-to-products)

* #### [What is a Coupon?](#What-is-a-Coupon?)
* #### [What type of Coupons are supported?](#What-type-of-Coupons-are-supported?)
* #### [Capturing coupon transactions (video)](#Capturing-coupon-transactions)

####   
[**FAQ's**](#FAQ's)

   * #### [Do coupons apply to all products?](#Do-coupons-apply-to-all-products?)
   * #### [What are the different types of coupons I can create?](#What-are-the-different-types-of-coupons-I-can-create?)
   * #### [Are coupon codes unique?](#Are-coupon-codes-unique?)
   * #### [What are the rules for creating a coupon code?](#What-are-the-rules-for-creating-a-coupon-code?)
   * #### [What is the coupon name? Is it unique?](#What-is-the-coupon-name?-Is-it-unique?)
   * #### [What is meant by limiting the total number of times a coupon code can be redeemed?](#What-is-meant-by-limiting-the-total-number-of-times-a-coupon-code-can-be-redeemed?)
   * #### [What is meant by limiting to selected products?](#What-is-meant-by-limiting-to-selected-products?)
   * #### [What is the redemption count shown in the list view?](#What-is-the-redemption-count-shown-in-the-list-view?)
   * #### [Will the coupons text box start appearing automatically in order forms?](#Will-the-coupons-text-box-start-appearing-automatically-in-order-forms?)
   * #### [I don't want to show the Apply coupon text box on my order form. How do I do that?](#I-don't-want-to-show-the-Apply-coupon-text-box-on-my-order-form.-How-do-I-do-that?)
   * #### [How to see the orders in which the coupon code has been applied?](#How-to-see-the-orders-in-which-the-coupon-code-has-been-applied?)
   * #### [Where are the coupon application details available?](#Where-are-the-coupon-application-details-available?)
   * [I want to set up a free product(s) is this supported?](https://help.gohighlevel.com/support/solutions/articles/48001224172-how-to-create-coupons-for-products#:~:text=to%20the%20order.-,I%20want%20to%20set%20up%20a%20free%20product%28s%29%20is%20this%20supported%3F,-Yes%2C%20this%20is)
  
  
---

# **How to create and add coupons to products**

  
**[](https://gohighlevel.slack.com/archives/C01TV1QJQCC/p1666286287775649)**

  
**Please Note:**

- Coupon codes are **not case-sensitive** and we will convert all coupon codes into uppercase  
  
**- Spaces and special characters** are not supported formats when creating Coupon codes  
  
- End customers can redeem a coupon code to get a **100% off on the cart value**. They would still require to enter their card details to save credit card info in case it is required for [upsells](https://help.gohighlevel.com/en/support/solutions/articles/48000980306) in the next steps.  
  
- Only Stripe can be used to give **100%** off on order amounts, this will **not** work with Paypal. In case both Stripe and Paypal exist, the Paypal option will be hidden.  
  
- Small text "_Card details will be used for verification purposes**"**_ will appear beside the card element during a **$0 checkout**
  
  
---

## **What is a Coupon?**

A coupon is an offer made by a business or organization (usually in exchange for your payment) where you receive a discount on something you purchase. 
  
  
## **What type of Coupons are supported?**

There are two ways to use a coupon:

1. **Percentage Coupon:** Offer a percentage-based discount on an order value
2. **Fixed Coupon:** Offer fixed discount irrespective of order value

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48258200897/original/SgSUTjo4oxqeSQ6c5AMqlap_URwh_U1hmA.png?1666281811)

**Please Note:**

- End customers can redeem a coupon code to get a **100% off on the cart value**. They would still require to enter their card details to save credit card info in case it is required for upsells in the next steps.  
  
- Only Stripe can be used to give **100%** off on order amounts, this will **not** work with Paypal. In case both Stripe and Paypal exist, the Paypal option will be hidden.  
  
- Small text "_Card details will be used for verification purposes**"**_ will appear beside the card element during a **$0 checkout**

##   

  
---

## **Capturing coupon transactions**

  
**Please Note:**

1. Coupon application details will be visible in the order details as a line item alongside individual products  
  
2. The coupon discount mentioned alongside each product will be the discount value per product  
  
3.The discount applied would be distributed according to the weights of values of products on which the discount was applied.   
  
    For**cart level discounts**, it will be distributed across all products(only one-time)     according to the weights of product values  
  
    For**discounts tied to specific products**, the discount will be applicable according to the     sum of the values of those items only and would be distributed according to the weights of     the product values (only one-time products)
  
  
---

# **FAQ's**

###   
**Do coupons apply to all products?**

Yes, coupons are applicable on both one-time and recurring products

  
###   
**What are the different types of coupons I can create?**

Two types: 

* **Percentage discount:** Offer a percentage-based discount on an order value
* **Fixed discount:** Offer fixed discount irrespective of order value

  
###   
**Are coupon codes unique?**

Yes, coupon codes are unique and no two coupons can be created with the same coupon code

  
###   
**What are the rules for creating a coupon code?**

Coupon codes can only contain alphanumeric values and are not case-sensitive. Using the Generate ability, the user can generate a 7-character alphanumeric coupon code

  
###   
**What is the coupon name? Is it unique?**

Coupon names can be used to refer to and relate to coupons for internal purposes. They must not be unique for every coupon, but we highly recommend using unique coupon names for proper identification

  
###   
**What is meant by limiting the total number of times a coupon code can be redeemed?**

Using this, you can limit the total number of successful redemptions you want to offer for the coupon code. This only includes successful redemption and is not dependent on the number of users redeeming the coupon code

  
###   
**What is meant by limiting to selected products?**

Using this, you can restrict the coupon usage to selected products only. This means that if you restrict coupon usage to product A, then the coupon can only be applied to product A

  
###   
**What is the redemption count shown in the list view?**

This displays the total number of successful redemptions of the coupon code done to date

  
###   
**Will the coupons text box start appearing automatically in order forms?**

If you have created a valid coupon code that can be applied to an order form, then the coupon text box will start appearing on the order form. In case of an order form where no applicable active coupon exists, the order form will not show the coupon application text box

  
###   
**I don't want to show the Apply coupon text box on my order form. How do I do that?**

You can disable the "Enable coupon codes" toggle inside the builder for the specific order form.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48258187347/original/NzsphO5dQMqqo8eCLjXQXCgxVSZhtApg6Q.jpeg?1666279283)

  
###   
  
**How to see the orders in which the coupon code has been applied?**

Click on Actions ➝ View History and this will redirect to the orders page where only specific orders in which the coupon code was successfully applied

  
**Status vs Actions for coupons:** 

| Actions vs Status | Active | Scheduled | Expired |
| ----------------- | ------ | --------- | ------- |
| Edit              | Yes    | Yes       | Yes     |
| Delete            | Yes    | Yes       | Yes     |
| View History      | Yes    | No        | Yes     |

  
###   
**Where are the coupon application details available?**

Order details would contain the coupon code and the discount offered per item against every product line item, in case a coupon code was successfully applied to the order.
  
  
### **I want to set up a free product(s) is this supported?**

Yes, this is possible! Purchasers can redeem a 100% OFF coupon code. They would still be required to enter their card details to save credit card info in case it's required for upsells/ downsells in the next steps.  
  
Currently, only Stripe can be used to give 100% off on order amounts, this will **not work with Paypal**. In case both Stripe and Paypal exist, the Paypal option will be hidden. 

During checking out with a cart that is $0, the text "_**Card details will be used for verification purposes**_" will appear beside the card element saying 

  
![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48264052849/original/Lk6B100HD1KcIjHzd6De0OhWnKGIxrll5g.png?1668707323)

![image](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48264053653/original/maWHirvq2ojH1ZlCz7LD3g0O4r870SQZXg.png?1668707559)

  