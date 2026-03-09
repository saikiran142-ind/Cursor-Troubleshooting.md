# Cursor-Troubleshooting.md
# 🖱 How to Fix Mouse/Cursor Not Working Issues

As an IT Support professional, follow these steps to fix mouse or touchpad freezing issues using only the keyboard.

### 1. Essential Keyboard Shortcuts (No Mouse Needed)
- `Win`: Open Start Menu.
- `Tab / Arrow Keys`: Navigate through options.
- `Spacebar`: Select/Check an option.
- `Enter`: Confirm/Open.
- `Shift + F10`: Right-click shortcut.

### 2. Quick Hardware Reset (Power Flush)
If the touchpad is frozen on a laptop:
1. Shutdown the laptop.
2. Unplug the power adapter.
3. **Press and hold the Power Button for 30 seconds**.
4. Plug back in and restart. This resets static electricity on the motherboard.

### 3. Driver Fix (Device Manager)
1. Press `Win + R`, type `devmgmt.msc` and hit Enter.
2. Use `Tab` to enter the list, scroll to **Mice and other pointing devices**.
3. Press `Right Arrow` to expand.
4. Press `Shift + F10` on the driver and select **Uninstall device**.
5. Restart the PC (`Alt + F4` > Restart) to let Windows reinstall the driver automatically.

### 4. BIOS Check
If the mouse doesn't work even during startup:
- Restart and press **F2/F10/Del** to enter BIOS.
- Navigate to **Advanced > Internal Pointing Device**.
- Ensure it is set to **Enabled**.

### 🖱 Advanced Mouse Issues
- **Single Click acting as Double Click:** Go to `main.cpl` > Buttons > Adjust Double-click speed to Middle.
- **Cursor Lagging:** Update Graphics Drivers and check Display Scaling (Recommended: 100%).
- **Invisible Pointer:** Uncheck "Hide pointer while typing" in Mouse Pointer Options.
- **Wireless Mouse Not Detected:** Replace battery and re-sync the USB Nano Receiver.

  ### 💻 Touchpad Specific Troubleshooting
- **Touchpad Shortcut:** Press `Fn + Touchpad Key` (varies by laptop: F3/F6/F7/F9) to re-enable.
- **Windows Settings:** Ensure **Touchpad is ON** in Settings > Devices > Touchpad.
- **Mouse Conflict:** Check "Leave touchpad on when a mouse is connected" setting.
- **Precision Drivers:** Update **I2C HID Device** or **Synaptics/ELAN** drivers in Device Manager.

