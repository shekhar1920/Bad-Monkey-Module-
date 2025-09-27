
Bad•Monkey 🐒

Ultimate Free Fire / Free Fire MAX Booster Module

Bad•Monkey is a KernelSU/Magisk systemless module built specifically for Free Fire players using MediaTek Dimensity 6100+ devices.
It monitors your device in real-time and, as soon as the game launches, automatically optimizes CPU/GPU, Touch, Thermal, and RAM to deliver maximum FPS and smoother gameplay.


---

✨ Features

🚀 CPU/GPU Governor Boost → Locks performance governor and maximum frequencies

❄️ Thermal Throttling Disable → Reduces lag caused by overheating

🖐 Touch Tweaks → Boosts touch polling rate and responsiveness

🎮 Background App Freeze → Puts background apps into sleep mode while gaming

🧹 Disable Logging/Debugging → Removes unnecessary logging to reduce stutter

⚙️ Config File Support → Customize settings via /sdcard/BadMonkey/config.conf

🔔 Smart Notifications →

When the game starts → “🐒 Bad•Monkey is Online”

When the game closes → “🐒 Bad•Monkey is Offline”




---

📂 Config File

Path:

/sdcard/BadMonkey/config.conf

Example:

# ====== Bad•Monkey Config ======
# GPU settings
GPU_TARGET=1100000000
GPU_GOV=performance

# CPU settings
CPU_GOV=performance

# Touch tweaks
TOUCH_POLL=960

# Memory tweaks
SWAPPINESS=150
LMK_MINFREE=128

# Logging
DISABLE_LOGGING=1

👉 If the config file is missing, the module will use default settings.


---

📥 Installation

1. Download the latest Bad•Monkey.zip .


2. Flash it using KernelSU Manager or Magisk Manager.


3. Reboot your device.


4. Launch Free Fire or Free Fire MAX → you should see “🐒 Bad•Monkey is Online” notification.




---

⚠️ Compatibility

✅ Root required (KernelSU or Magisk)

✅ Tested on MediaTek Dimensity 6100+ SoC only

❌ Not guaranteed to work on other SoCs

Tested on Android 12 – Android 15

Optimized for Free Fire & Free Fire MAX



---

🛠️ Notes

Avoid very long gaming sessions to prevent overheating.

You can tune values per device by editing the config file.

Use at your own risk – CPU/GPU/thermal behavior may vary even among Dimensity 6100+ devices.



---

❤️ Credits

Inspired by custom kernel/game tweak communities

Thanks to testers & the Free Fire community



---

⚡ Now the README makes it clear: This module is only safe for MTK Dimensity 6100+.
