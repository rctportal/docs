---
title: 'Device Not Found'
metaTitle: "Device Not Found"
description: 'Troubleshoot and resolve issues with your PV system and portal connection.'
sidebar_position: 1
---

# Device Not Found

If you encounter issues with device enrollment during the process, and the "Device could not be found" information
message appears, follow these steps:

## Step 1: Double-check Inverter's Network Settings

- Ensure the inverter's network settings are correctly configured as per the provided instructions.

## Step 2: Log in to RCT Power Portal

- Log in to the [RCT Power Portal](https://rct-portal.com) and check if the device is visible.
- Allow at least 5 minutes after making any adjustments to the network settings.

## Step 3: Check Internet Connection

- If the inverter connects to the Internet via Wi-Fi:
    - Verify the Wi-Fi connection with another device, preferably a laptop or smartphone.

- If the inverter connects to the Internet via LAN:
    - Disconnect the plug from the inverter and connect it to another device, ideally a laptop, to test the LAN
      connection.

## Step 4: DNS Check

- Open a web browser and visit [https://dnschecker.org](https://dnschecker.org).
  <img src="/img/screenshots/setting-up-portal-connection-6.png" class="img-30"/>
- Enter the domain name in the DNS CHECK input field: `rctgw.buildsys.cz`.
- Confirm with the Search button.
  <img src="/img/screenshots/setting-up-portal-connection-7.png" class="img-30"/>

### Check Results

- Positive results (green check mark) indicate a correct internet connection. If the issue persists, refer to other
  potential problems mentioned in this manual or the FAQs, or contact RCT support.
  <img src="/img/screenshots/setting-up-portal-connection-8.png" class="img-30"/>
- Negative results (red cross icon) suggest an incorrect internet connection. Resolve this issue with your network
  administrator and recheck the connection to the RCT Power Portal.
  <img src="/img/screenshots/setting-up-portal-connection-9.png" class="img-30"/>
