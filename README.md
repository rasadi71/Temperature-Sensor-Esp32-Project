# Step-by-Step: Add ESP32 to Arduino IDE

### ✅ Step 1: Open Arduino IDE

Launch the Arduino IDE on your computer.

### ✅ Step 2: Open Preferences

Go to: File → Preferences

Look for the field: 👉 "Additional Board Manager URLs"

### ✅ Step 3: Add ESP32 URL

Paste this URL into the field:
```bash

[https://dl.espressif.com/dl/package_esp32_index.json](https://dl.espressif.com/dl/package_esp32_index.json)

```

Note: If there is already a link there, add a comma first, then paste the new link.

#### Example: old_link, https://dl.espressif.com/dl/package_esp32_index.json

Press OK.

### ✅ Step 4: Open Board Manager

Go to: Tools → Board → Boards Manager

### ✅ Step 5: Install ESP32 Package

In the search box, type: esp32

### Look for: 👉 ESP32 by Espressif Systems

Click Install.

### ✔ Supported Boards

This adds support for boards such as:

ESP32 Dev Module

NodeMCU-32

DOIT ESP32
