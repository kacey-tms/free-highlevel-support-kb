**Date Updated:** 2024-11-28T14:41:47.000Z

**TABLE OF CONTENTS**

* [Overview](#Overview)
* [Action Name: Book Appointment](#Action-Name%3A-Book-Appointment)
* [How to Use](#How-to-Use)
* [Conditional Logic (Adding an If/Else Condition)](#Conditional-Logic-%28Adding-an-If/Else-Condition%29)
* [New Workflow Filter for Appointment Status Trigger](#New-Workflow-Filter-for-Appointment-Status-Trigger)

---

### **Overview**

  
The **Book Appointment** action enables the creation of new appointments based on specified times and in specified calendars. Users can now configure a **Book Appointment** action through workflows, which allows appointments to be created based on trigger events. This is ideal for businesses looking to automate appointment bookings through specific triggers.

  
**Example Use Case:** If a form submission or data from an inbound webhook is received, a follow-up appointment can be scheduled automatically for a set time.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155036786077/original/VUY_ceX2b6zuFoWdBH1pW1IopQ3nAHA-3w.png?1732001015)

  
---

### **Action Name: Book Appointment**

  
### **How to Use**

1. **Navigate to**: `Automations > Create New Workflow > Start From Scratch`.
2. **Add a Trigger** (e.g., `Form Submitted`).
3. **Add an Action**:  
   * Select `Add Action > Book Appointment`.  
   * **Enter the Action Name**.  
   * **Choose the Calendar** where the appointment will be booked.  
   * **Set the Appointment Date and Time**:  
         * **Standard**: A fixed date and time applied to all appointments created by this workflow.  
         * **Dynamic**: A variable start date and time for different appointments. This can use data captured from inbound webhooks or custom values.  
         * ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155036786438/original/Q5tsHdRf-PmE6jRDDFe91fOfhPpy_NfwyQ.png?1732001412)  
         * ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155036786459/original/h55WHaUJnnsQWzMJkdZRMeWClZ0-ADPGFw.png?1732001425)  
         * ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155036786474/original/yXuE6PpY1baD2PFVF4yL6tgnTwzivfx1Og.png?1732001437)  
         * ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155036786482/original/NRgizd5txTvPI_tyYf_kjd59eSLwhL449g.png?1732001449)
4. **Select a Team Member**:  
   * Choose `Calendar Default` (team member selected through round-robin or default settings).  
   * Or, specify a particular team member for the booking.
5. **Additional Settings**:  
   * **Override Availability**: If enabled, the system will book the appointment without checking availability. If disabled, the system will ensure availability before scheduling.

  
**Note**: For dynamic start dates and times, ensure your format is compatible. Use the `Date Time Formatter` action to convert the date and time format if necessary.

  
**Supported Date and Time Formats**:

* `MM-DD-YYYY HH:MM` (e.g., `12-21-2021 08:30 AM`)
* `DD-MMM-YYYY HH:MM` (e.g., `21-OCT-2021 08:30 AM`)

  
---

### **Conditional Logic (Adding an If/Else Condition)**

  
You can also add an **If/Else Condition** to check if the appointment was successfully booked. To implement the conditional logic:

  
1. Click on Add Action and select **If/Else.**
2. Enter the **Action Name.**
3. Set the **Branch**Conditions:  
   * Under Branch, select Book Appointment and choose the specific action created earlier. In the adjacent field, select True for "Appointment booked successfully" and False for "Appointment not booked".  
   * **If Booked (True)**: Define next steps, such as sending a confirmation email.  
   * **If Not Booked (False)**: Specify alternative actions, like notifying the user by email.

---

### **New Workflow Filter for Appointment Status Trigger**

  
We have introduced a new filter in the Appointment Status Trigger. Now, whenever an appointment is booked or edited via the workflow, you can use the 'Modified By' filter to control when the workflow should fire.

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155036786733/original/iXDLon-lCDACFhWUl-hyXsJsoNLEwBt8hg.png?1732001697)
  
  
---

### **Limitations**

* Calendars that have 'Recurring' enabled cannot be selected for the 'Book Appointment' action