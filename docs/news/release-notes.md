---
title: 'Release Notes'
metaTitle: "Release Notes"
description: ''
sidebar_position: 1
pagination_next: null
pagination_prev: null
---

# Release Notes

## Version 1.4.2 [2023-12-18]

### New Features

#### End Users

- **Improved Energy Stats Date Picker**: Enhanced date selection on the Installation Dashboard with added interval selectors, navigation arrows, and defaulting to 'day' with the current date.

- **Show Slave Data on Offline Systems**: End users can now access slave data even during communication issues with systems (offline/error installations).

- **Redesigned Registration Process**: Streamlined registration to prevent incomplete installations or accounts.
  - Removed type of registration selection.
  - Clicking 'Sign Up' redirects to Personal Registration page.
  - Two-step process:
    1. Email and inverter serial number confirmation.
    2. Completion of necessary fields for a new account/installation.
  - Email and inverter serial number are non-editable after progressing to the second step.
  - No data saved until successful account creation.
  - After creating a new account, automatic login and redirection to the user dashboard.
  - Settings Page: 'Street' field no longer required; fixed user menu in the top right corner.

#### Company Users

- **Filtering Master-Slave Installations**: Company users can filter master-slave installations on the installation list with a new 'Master-Slave' value in the 'Type' column.

- **Gridview Filters Highlight**: Company users now see highlighted filter buttons indicating active filters.
  - Temporarily changes the color of the 'Cancel filters' button when filters are active.
  - Remember installation list filters for each user:
    - Currently selected filters, sorting options, and paging options are cached.
  - Added a new icon to the 'Type' column indicating master-slave systems on the installation list.

### Bug Fixes

#### End Users

- **Dashboard**: Resolved an issue where energy stats graphs displaced data labels.

#### Company Users

- **Last Contact Format Date Fix**: Resolved the last contact format date issue.
- **Users Management Fixes**: Preserved filters during sorting in Users Management.
- **Localization and Device Management Fixes**: Fixed filter buttons overlap and button icon issues.
- **Installation List Bottom Buttons Fix**: Resolved the issue of bottom buttons overlapping.

---

## Version 1.4.1 [2023-11-09]

### New Features

#### End Users

- **Reports Toggle Button**: Users can switch displayed data between total or detailed values with a toggle button.
  - Improved styles for mobile devices - padding in the chart and its legend.

- **Installation Settings Redesign**: One-step installation settings.
  - Added the possibility to write text for search to companies dropdown list, a button for clear selected company.
  - When the installation is 'Unclassified', on the UI side, there is no selected company.
  - Added validation to 'Total Installed Capacity' on PV Panel and Battery: Must be a non-negative value.

- **Added Exception for Old Battery Serial Numbers**: When the BMS serial number is '0180A000000000', it's identified as a battery master device.

- **Total/Detail View for Range 'All'**: The toggle button is visible for range 'All', and the user can switch between historical total numbers or year subtotals.

#### Company Users

- **Hideable Columns on Gridview**: In the list of installations admins can use the button titled "Edit Columns" at the bottom right corner.

- **Added Column 'Created', Enabled Sorting, and Updated CSV Export**:
  - Added the column 'CREATED' to the installation list.
  - Enabled sorting of the installation list by 'PV INST. POWER' and 'BATTERY INST. CAPACITY'.
  - Added columns 'BMS SW VERSION' and 'CREATED' to CSV reports.

### Bug Fixes

#### End Users

- **Installation Detail Improvements**:
  - Removed the subtitle (device name).
  - Renamed "others" to "current values".
  - Renamed "power battery master" to "battery info".
  - Added values (AC power, external power, and battery power) to the inverter.
  - Removed the value of external power from the slave inverter.
  - Buttons for the claim process moved outside the scrollbar.
  - Rounded values of heat sink temperatures.

- **Remember Series Selection During Date Changes**: Improved series selection retention during date changes.

- **Zoom-Out Limited to 24 Hours on Power Reports**: Restricted zoom-out functionality to 24 hours on power reports.

- **Check Null Value of Battery SN**: Added a check for the null value of the serial number on the Installation Detail page to display as much data as possible.

#### Company Users

- **Unifying Menu Titles & Dialog Errors**: Left menu list items are pluralized nouns (Installations, Users, Companies, Manufacturers).
  - Unified error message presentation in the edit user/company dialogs (Admin, Manufacturer & Company level).

- **Button 'Edit Columns' Translated to CZ and DE**: Resolved translation issue for the button 'Edit Columns'.

For any issues or feedback, please let us know.
