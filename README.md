# blue_check

Install expect:
sudo apt-get install expect

Run:
sudo python3 bluetooth_security_check.py

-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
To Customize the Payload:
Hex Keycode Mapping:

Use HID keycodes to map keystrokes to hex values.

Example payload to open a Linux terminal (Ctrl+Alt+T):
# Hex codes for Ctrl+Alt+T
payload = "00 00 1C 00 00 00 00 00"  # Modify this

Real-World Example:
To open a URL in Chrome (replace with your test URL):
# Sequence: Win + R → "chrome.exe https://your-test-url.com" → Enter
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------

Limitations:
Pairing Requirements: Most devices require manual confirmation for Bluetooth connections.

OS Compatibility: Tested on Linux; Windows/macOS may block unexpected HID devices.

Ethics: Never use this on unauthorized devices.

