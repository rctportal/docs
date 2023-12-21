---
title: 'Setting Up Portal Connection'
metaTitle: "Setting Up Portal Connection"
description: 'Setting Up RCT Power Portal Connection'
sidebar_position: 1
---
# Setting Up RCT Power Portal Connection

In order to visualize the values of your PV system in the RCT Power Portal, you must follow these steps:

:::tip
Please note that the Control Software version 5369 or higher must be installed on the RCT Power Inverter to enable an error-free connection to the RCT portal.

For trouble-free operation, we recommend connecting your inverter to your home network via LAN or using a dLAN® Powerline adapter.

Inverters equipped with the WiFi_C1 module cannot be registered in the portal.

The WiFi_C1 module is easily recognizable by its missing LAN port on the corresponding power storage.

The following inverters are equipped with a WiFi_C2 module and a LAN connection and can be registered:

- Power Storage DC 6.0 ab Seriennummer 0065A4630282
- Power Storage DC 5.0 ab Seriennummer 0065A4530049
- DC 4.0 power storage from serial number 0065A4430027
- All Power Storage DC 8.0 and 10.0 models

Power Storage AC systems and installations with more than one Power Storage DC cannot be assigned in the current version of the RCT Power Portal.
:::

## Prerequisites

Before starting the setup process, ensure the following:

- Download the "RCT Power App" from the [Google Play Store](https://play.google.com/store/apps/details?id=com.rctportal.rctpowerportal).

## Setup Process

### Step 1: Open RCT Power App and Device Selection

- Open the RCT Power app on your mobile device.
- Tap the "Device Selection" menu.

<img src="/img/screenshots/setting-up-portal-connection-1.png" class="img-30"/>

### Step 2: Activate Your System

- Select your system from the list and activate it.
- Once connected, the system name is displayed in green in the app's header.

<img src="/img/screenshots/setting-up-portal-connection-2.png" class="img-30"/>

### Step 3: Access Settings

- Tap the gear icon to access the settings menu.

### Step 4: Login to System and Access Network Settings

- The LOGIN screen appears.
- Tap LOGIN to open the password dialog. Use the system owner's password.
- Select "NETWORK SETTINGS" from the menu.

<img src="/img/screenshots/setting-up-portal-connection-3.png" class="img-30"/>

### Step 5: Connect to RCT Power Portal

- The network settings are loaded.
- Check the box next to "Connect Portal" to initiate the connection.
- Accept the RCT Privacy Policy when prompted.

<img src="/img/screenshots/setting-up-portal-connection-4.png" class="img-30"/>

### Step 6: Network Settings Configuration

- Android devices automatically load required network settings.
- For iOS devices:
  - IP-Address: rctgw.buildsys.cz
  - TCP-Port: 8899
  - Check your entries for correctness and tap "Next".

<img src="/img/screenshots/setting-up-portal-connection-5.png" class="img-30"/>

### Step 7: Complete Configuration

- On the next screen, select "Obtain IP address automatically". It is enabled by default and required.
- Click FINISH to update.
- Messages indicating progress will appear: Apply changes, Save finish changes, Finish.

### Step 8: Finalize Setup

- Press "Finish" again to complete the setup and return to the settings menu.

Now your installation is connected to the RCT Power Portal. Ensure your system is registered on the portal for data visualization.

## Troubleshooting Device Enrollment Issues

In the event that device enrollment issues occur during the enrollment process, and the "Device could not be found" information message is displayed, follow these steps to troubleshoot:

### Step 1: Double-check Inverter's Network Settings

- Ensure the inverter's network settings are configured correctly based on the provided instructions.

### Step 2: Log in to RCT Power Portal

- Log in to the [RCT Power Portal](https://rct-portal.com) and check if the device can be found.
- Allow at least 5 minutes after any adjustment of the network settings.

### Step 3: Check Internet Connection

- If the inverter is connected to the Internet via a Wi-Fi connection:
  - Verify the Wi-Fi connection with another device (ideally a laptop or smartphone).

- If the inverter is connected to the Internet via a LAN connection:
  - Disconnect the plug from the inverter and connect it to another device, ideally a laptop, to test the LAN connection.

### Step 4: DNS Check

- Open a web browser and visit [https://dnschecker.org](https://dnschecker.org).
<img src="/img/screenshots/setting-up-portal-connection-6.png" class="img-30"/>
- Enter the domain name in the DNS CHECK input field: `rctgw.buildsys.cz`.
- Confirm with the Search button.
<img src="/img/screenshots/setting-up-portal-connection-7.png" class="img-30"/>

#### Results:
- If positive results are displayed (green check mark), the internet connection is correct, and the issue may lie elsewhere. Check other potential issues mentioned in this manual or the FAQs, or contact RCT support.
<img src="/img/screenshots/setting-up-portal-connection-8.png" class="img-30"/>
- If negative results are displayed (red cross icon), the internet connection is not correct. Have your network administrator resolve this issue and check the connection to the RCT Power Portal again.
<img src="/img/screenshots/setting-up-portal-connection-9.png" class="img-30"/>