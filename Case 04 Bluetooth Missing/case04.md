<p align="center">
<img src="https://github.com/alexandrpaul/win-trou/blob/e14f2109eb369a2514fc354fddbd0b4d6cb1723e/Case%2001%20Slow%20PC%20Performance/logo.png"/>
</p>

# Case 04: Missing / Disabled Bluetooth Adapter

## Issue Description
The Bluetooth toggle is missing in **Settings** → **Bluetooth & Devices**, preventing device pairing.

## Root Cause
The Bluetooth adapter is disabled in **Device Manager**.

## Troubleshooting Steps
1. Open **Device Manager** and navigate to the **Bluetooth** section.  
2. Look for the adapter with a **down arrow**, indicating it’s disabled.  
3. **Right-click** the adapter and select **Enable device**.  
4. Check **Settings** → **Bluetooth & Devices** to confirm the toggle reappears.  
5. Pair the Bluetooth device (for this instance, *wireless earphones*) to verify functionality.

 **Before:**  
![Bluetooth adapter disabled](https://github.com/alexandrpaul/win-trou/blob/2ca4fae9713b35bc681ab39a6c94fbe3ea01031e/Case%2004%20Bluetooth%20Missing/img1.png)

 **After:**  
![Bluetooth restored](https://github.com/alexandrpaul/win-trou/blob/2ca4fae9713b35bc681ab39a6c94fbe3ea01031e/Case%2004%20Bluetooth%20Missing/img2.png)

## Resolution
The adapter is re-enabled, Bluetooth functionality is fully restored.

## Lessons Learned
Always check the adapter status in **Device Manager** before reinstalling drivers or performing other interventions.
