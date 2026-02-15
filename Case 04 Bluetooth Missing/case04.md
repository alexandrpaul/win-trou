# Case 06: Missing / Disabled Bluetooth Adapter

## Issue Description
Bluetooth toggle missing in Settings, Bluetooth & Devices.

## Root Cause
Bluetooth adapter disabled in Device Manager.

## Troubleshooting Steps
1. Opened **Device Manager, Bluetooth section**.  
2. Found adapter with a **down arrow** (disabled).  
3. Right-clicked, **Enable device**.  
4. Verified Bluetooth toggle appeared in Settings.  
5. Paired Bluetooth Earphones successfully.

 **Before:**  
![Bluetooth adapter disabled](https://github.com/alexandrpaul/win-trou/blob/2ca4fae9713b35bc681ab39a6c94fbe3ea01031e/Case%2004%20Bluetooth%20Missing/img1.png)

 **After:**  
![Bluetooth restored](https://github.com/alexandrpaul/win-trou/blob/2ca4fae9713b35bc681ab39a6c94fbe3ea01031e/Case%2004%20Bluetooth%20Missing/img2.png)

## Resolution
Enabled adapter, Bluetooth working normally.

## Lessons Learned
Always verify the adapter status in Device Manager before reinstalling drivers.
