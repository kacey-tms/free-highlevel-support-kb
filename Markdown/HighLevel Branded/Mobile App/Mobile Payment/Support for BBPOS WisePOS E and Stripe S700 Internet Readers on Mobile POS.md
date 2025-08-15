**Date Updated:** 2025-08-06T00:16:21.000Z

  
This article shows you how to pair Stripe’s Wi-Fi–enabled WisePOS E and S700 readers with the HighLevel, LeadConnector, or your own white-label mobile app (v 3.103.4). Once connected, you can take secure, card-present payments right inside the POS—no dongles, cables, or browser windows required.

**TABLE OF CONTENTS**

* [What Are Stripe Internet Readers? ](#What-Are-Stripe-Internet-Readers?%C2%A0)
* [Key Benefits of Using WisePOS E & S700 With Mobile POS ](#Key-Benefits-of-Using-WisePOS-E-&-S700-With-Mobile-POS%C2%A0)
* [Prerequisites ](#Prerequisites%C2%A0)
* [How to Register a WisePOS E or S700 Reader](#How-to-Register-a-WisePOS-E-or-S700-Reader)
* [Taking a Payment With a Registered Reader ](#Taking-a-Payment-With-a-Registered-Reader%C2%A0)
* [Troubleshooting & Best Practices ](#Troubleshooting-&-Best-Practices%C2%A0)
* [Frequently Asked Questions ](#Frequently-Asked-Questions%C2%A0)
* [Next Steps ](#Next-Steps%C2%A0)

---

# What Are Stripe Internet Readers? 

Stripe Internet Readers are standalone payment terminals that connect to your phone or tablet over local Wi-Fi. Because they’re internet-connected, every tap, insert, or swipe flows directly through Stripe’s PCI-certified infrastructure for end-to-end encryption. Pairing them with HighLevel turns any iOS or Android device into a countertop-to-mobile checkout station.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050975414/original/p2hOMn20Xe3PD5X3UDZArIyoe9O79O3Vzg.png?1754419486) 

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050975415/original/lijrpn42R4fqFvywh3TX85_lRQ3I0t8-rw.png?1754419486)

## Key Benefits of Using WisePOS E & S700 With Mobile POS 

Knowing the advantages helps you choose the right hardware for every checkout lane or roaming associate.

* All-in-one hardware – Accept chip, tap, and magnetic-stripe payments out of the box.
* Speedier lines – Customer-facing prompts slash cashier time.
* Unlimited readers per location – Register as many devices as you need; each appears in the Payment Instruments list.
* Unified reporting – In-person and online sales land in the same HighLevel Payments dashboard.
* Automatic compliance – Firmware updates add new card-scheme requirements with no manual effort.

## Prerequisites 

Confirm these items before you begin to avoid pairing errors and failed transactions.

1. A live Stripe account connected in Payments → Integrations
2. Mobile device and reader on the same 2.4 GHz or 5 GHz Wi-Fi network.
3. Device enrolled in the HighLevel / LeadConnector public beta on the App Store or Google Play.
4. Mobile-app version v 3.103.4 or later

## How to Register a WisePOS E or S700 Reader

Pairing links the physical terminal to your sub-account so it appears at checkout.

1. Power on the reader – On the idle screen, tap Generate Pairing Code to display a six-digit code.  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155050975413/original/hUbO8pDxbK2aPlEqzCkbTTsTXV6zRG0-gQ.png?1754419486)

  
1. Open the mobile app and select the correct sub-account.
2. Navigate to Settings → Payment Devices → Pair a New Hardware Device → Internet Readers.
3. Enter a reader name you’ll recognize at checkout—e.g., FrontCounter\_WisePOS1.
4. Type the pairing code shown on the reader.
5. Tap Pair. Look for the toast “FrontCounter\_WisePOS1 registered successfully.”
6. Repeat Steps 1-6 for any additional readers on the network.

## Taking a Payment With a Registered Reader 

Once paired, selecting a reader is as easy as choosing a card-on-file.

1. Start a sale in the POS and add items to the cart.
2. On Payment Instruments, choose the reader you want to use.
3. Present the reader to the customer. They can tap, insert, or swipe. A 5-minute timer counts down on the mobile screen.
4. Wait for confirmation. The reader shows “Approved,” and the sale appears instantly in Transaction History.

## Troubleshooting & Best Practices 

Use these quick fixes to keep every lane moving.

| Symptom                             | Fix                                                                                             |
| ----------------------------------- | ----------------------------------------------------------------------------------------------- |
| Reader not found                    | Verify both devices are on the same SSID; restart the reader; ensure ports 443 & 4070 are open. |
| Pairing code expired                | Codes last 60 seconds—generate a new one on the reader and try again.                           |
| Payment timer expired               | Relaunch the sale; ask the customer to keep the card in place until the beep.                   |
| Need to move readers between stores | Unpair in Payment Devices, then repeat the pairing steps on the new Wi-Fi network.              |

  
##   

---

## Frequently Asked Questions 

Q : How many internet readers can I register in one sub-account?  
 A : Unlimited. Each reader shows up individually in Payment Instruments.

Q : Do I need Bluetooth?  
 A : No. WisePOS E and S700 pair over local Wi-Fi.

Q : Can customers add a tip on the reader?  
 A : Yes. Enable Prompt for Tip under POS Settings → Gratuity.

Q : Can I refund these payments from the web app?  
 A : Absolutely—the refund flow is identical to online Stripe charges.

Q : Do the readers work offline?  
 A : Transactions require an active internet connection. If Wi-Fi drops, accept cash or card-on-file.

### Next Steps 

1. Update all checkout devices to v 3.103.4 to unlock reader support.
2. Train staff on tap-to-pay etiquette for faster lines.
3. Bookmark the Hosting Status Page for real-time uptime and incident alerts.
  
  