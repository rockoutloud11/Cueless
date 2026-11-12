# Cueless

Cueless is an accessible Windows app for the **Corsair HS80 RGB Wireless** headset. It works fully with NVDA and other screen readers, and with large text and high contrast, so you don't have to use iCUE.

Cueless is not made by, affiliated with, or endorsed by Corsair. Corsair, iCUE and HS80 are Corsair's trademarks. Use it at your own risk. It comes with no warranty of any kind.

## Download

1. Go to the **Releases** page of this repository and open the newest release.
2. Download **Cueless-Setup** (the .exe file).
3. Run it. Windows SmartScreen may warn about a new app. If it does, choose **More info**, then **Run anyway**.
4. Make sure iCUE isn't running (see Requirements below).
5. Setup shows one window. Choose the install folder and options, then press **Install**. Nothing is installed before that, and no administrator rights are needed.
6. To open Cueless later, press the Windows key and type **Cueless**.

To update, use **Check for updates** on Cueless's General tab. It downloads the new setup, installs it over your copy and keeps your settings.

To remove Cueless, open Windows Settings, then Apps, then Installed apps, and uninstall it from there.

## What it does

- **Voice prompts** in a real voice for:
  - mic muted and unmuted
  - headset on and off
  - receiver plugged in and unplugged
  - mute reminder
  - low and critical battery
  - charging started and fully charged
  - sidetone on and off
  - EQ preset changes

  You can turn each one on or off. You can also switch to the headset's own tones instead.
- **EQ:** Corsair's five presets (Pure Direct, Bass Boost, Clear Chat, FPS Competition, Movie Theater) plus up to five custom presets. Pressing the volume wheel switches presets.
- **Sidetone:** hear your own voice, with a level control.
- **Headset volume and mic level.**
- **Battery and charging status**, low battery warnings, and the auto sleep setting.
- **Lights:**
  - solid color, color cycle, breathing, or off
  - brightness
  - the mic light can show mute status
- **Works over the receiver or the USB cable.**
- **Notification area icon** with the battery level and mic state, and an option to start with Windows.
- **Updates itself** from this page when you ask it to.
- **Dark, light, or Windows colors, and text from 100 to 200 percent.**

The full guide is **Cueless help.txt**, installed with Cueless and opened from the Help button.

## Requirements

- Windows 10 or 11, 64-bit.
- Corsair's audio driver for the EQ. It's installed with iCUE.
- **iCUE must not be running.** iCUE and Cueless both try to control the headset and get in each other's way. Before using Cueless:
  1. Quit iCUE: in the notification area, open iCUE's menu and choose Quit.
  2. Stop iCUE starting with Windows: open Windows Settings, go to Apps, then Startup, and turn off **iCUE**.

  Keep iCUE installed: Cueless needs its audio driver for the EQ, and iCUE is still how you update the headset's firmware. Quit Cueless before opening iCUE for that.
- Everything else works without any Corsair software.

## Firmware

Cueless can't update the headset's firmware. Only iCUE can. Corsair's web firmware updater doesn't support this model.
