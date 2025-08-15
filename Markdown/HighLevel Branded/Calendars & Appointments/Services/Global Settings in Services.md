**Date Updated:** 2025-05-22T21:58:12.000Z

**TABLE OF CONTENTS**

* [In-App Settings](#In-App-Settings%3A)
* [Booking Page Settings](#Booking-Page-Settings%3A)
* [Payment Settings](#Payment-Settings)
* [Service Settings](#Service-Settings)
* [Additional Settings](#Additional-Settings)

  
Global Settings allow you to configure essential settings that will be applied across all services. These are divided into five main sections:

1. **In-App Settings**: Configure options related to your in-app platform.
2. **Booking Page**: Manage settings for your customer-facing booking widget.
3. **Payment Settings:**
4. **Service Settings**: Control options for service bookings and appointments.
5. **Additional Settings**: Miscellaneous settings for added functionality.

---

### **In-App Settings:**

* **View Options**: Choose which day the calendar view should start on: Monday, Saturday, or Sunday.
* **Offer Online Services**: Toggle this on if you provide services online. You can enable integrations with Google Meet, Microsoft Teams, or Zoom. Ensure that staff has connected their preferred video conferencing tool from the Connections tab.
* **Enable** **Multiple Locations**: Enable this if your business operates in multiple locations. This will allow you to create and display more than one location on your booking page, so customers can choose where to book.
* **Enable Resources**: If your business uses resources like rooms, spaces, or tools, toggle this on to manage and track them. It will prevent double bookings and help ensure the correct resources are reserved for services. Enabling this will add a "Resources" tab where you can configure these settings.
* **Enable Add-ons**: Toggle this on if your business offers add-ons or extras when booking a service. This can help upsell additional services. Enabling this will add an "Add-ons" tab for configuration.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047089451/original/WWtMcf0BmRNG1ld_pm0pgmrkMUbqseR-Ig.png?1747930942)

  
---

### **Booking Page Settings:**

###   

### **1\. Customize Booking Page:**

* **Company Name & Logo**: Add your company name and upload your company logo, which will be displayed on your booking page.
* **Booking Page Order:** Decide the flow of your booking page. In case of multiple locations, choose whether customers select a service first or a location first before proceeding with the booking.
* **Account Slug:** Your account slug is a unique identifier used as the base for all your service URLs.
* **Theme**: Choose between a light or dark theme for your booking page, which affects the header, footer, and widgets.
* **Primary Color**: Set the color for all actions like buttons and date selection.
* **Background Color**: Choose the color for the background of the booking page.
* **Button Text 1**: Customize the button text that appears when customers select a service (e.g., 'BOOK')
* **Button Text 2**: Set the text for the final button on the booking page, where customers complete  
their appointment (e.g., 'Schedule Appointment')
* **Preview**: Preview your booking page with your changes applied.
* **Insert Custom Code**: Add custom CSS to further customize the look and feel of your booking page. Simply paste your code and save to apply changes.

  
**2\.** **Additional Settings**  

* **Allow Staff Selection:** Enable this if you want customers to select a staff member during booking. Otherwise, the system will assign a staff member automatically based on availability and round robin logic.
* **Hide 'Any Available' from Staff Selection**: If staff selection is enabled, you can hide the "Any Available" option, requiring customers to select a specific staff member.
* **Allow Multiple Service Selection:** Enable this to let customers book multiple services in one session.
* **Auto-Assign Staff Based On:** Used when the customer doesn’t select a staff member. The system will follow this preference to assign one automatically.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047089486/original/4i_h11vq1qlmk1XWJnXHjkXKJ0VlGkvJIw.png?1747931029)

**3\. Forms** 
  
* **Select Form:** Choose the form that should be displayed when booking services. You can use the Default Form (First Name, Last Name, Phone, and Email) or create a custom form in _Sites > Forms_. The form helps in collecting booker's information and create a subsequent contact in the system.
* **Pre-populate Fields (Sticky Contacts):** This feature remembers customer information using browser cookies. It pre-populates the booking form for returning customers. This should only be enabled when customers are filling out the form themselves. If different customers use the same browser, the information may get overwritten.
* **Consent Checkbox:** Enable this to obtain customer consent during the booking process. You can customize the consent message. This is only available when using the Default Form.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047089499/original/dEY6RwUTPlKCTAwhKZ5pUUQfCR0Uiz7eSg.png?1747931046)

**4\. Confirmation Page:**

* **Post Booking:** After a booking is made, choose to show a custom message on the confirmation page (Default) or redirect the customer to another page.
* **Redirect URL:** Add the URL of the page where bookers should be redirected after a successful booking.

**![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047089548/original/IU0Pfc5jV3vWVBJn2wp3soRIfINHbF7FdQ.png?1747931071)**

---

#### **Payment Settings**

  
* **Test Mode vs. Live Mode**: Enable "Test Mode" to simulate the booking and payment process. Once testing is complete, toggle to "Live Mode" to start accepting real payments.
* **Currency**: Select the currency in which payments will be displayed and collected. This will apply to all services. If you are changing your currency, please ensure that the corresponding pricing for each service is updated accordingly.
* **Booking Payment Options:** Set how payments are handled on your booking page. This will determine what your customers see during checkout.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047089605/original/dY19roPDIb9NP64pQ-3_y4egSYDfDyHTsw.png?1747931099)

---

### **Service Settings**

* **Service Interval**: Determines how often time slots are available for booking. For example: If the interval is set to 1 hour, available slots will be shown every hour (e.g., 9:00 AM, 10:00 AM). If the interval is set to 30 minutes, available slots will appear every 30 minutes (e.g., 9:00 AM, 9:30 AM, 10:00 AM). This allows the booking slots to be spaced out based on the chosen interval.
* **Minimum Scheduling Notice**: The minimum time required after which an appointment cannot be booked. For example, if the notice is set to 2 hours, a 10 AM slot cannot be booked after 8 AM on the same day.
* **Date Range**: Controls how far into the future customers can book appointments. If set to 1 month, only slots for the next 30 days will be available.
* **Look Busy**: Allows you to hide a percentage of your available time slots, making it appear as though you have fewer open slots and are in high demand.
  
  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155047089610/original/ohRu0KNX_kehM4h0fv8stofvkQYnrD9bdw.png?1747931116)  

####   

#### **Cancellation & Reschedule**

* **Allow Cancellation**: When enabled, you can set an expiration time to your cancellation link. This link will expire at the set time before the appointment, preventing last-minute cancellations.
* **Allow Rescheduling**: Similar to cancellation, enabling this lets you set an expiration time to the rescheduling link. It will expire as configured before the appointment time.
* **Auto Confirm New Appointments**: New bookings will automatically be marked as confirmed by default. If disabled, appointments will be unconfirmed, allowing manual review before confirmation.

---

### **Additional Settings**

* **Contact Assignment**  
   * **Assign contacts to service staff members upon booking**: When enabled, this updates the contact's assigned user to the staff member handling their appointment. For example, if Contact A's assigned user is User A, but Contact A books an appointment with User B, the contact's assigned user will switch to User B.  
   * **Skip assignment if the contact already has an assigned user**: If enabled, this setting prevents reassignment of a contact who already has an assigned user. It will only update contacts that currently have no assigned user to the appointment's owner.
* **Facebook Pixel ID**: Enter your Facebook Pixel ID here to track events triggered through the booking process.
* **Lock timezone on the booking page**: This option locks the displayed timezone on the booking page, preventing users from changing it. It’s particularly useful for in-person services, ensuring slots are shown in your set timezone regardless of the booker’s location.

---

  