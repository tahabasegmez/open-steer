# OpenSteer

Use your phone as a racing wheel or a gamepad for PC games. The phone tilts like a steering
wheel (or shows pedals, buttons and sticks); the PC sees an Xbox 360 or DualShock 4 controller.

This repository hosts the **PC app downloads**. Get the latest version from
[Releases](https://github.com/tahabasegmez/open-steer/releases/latest).

## Install

**Windows 10 / 11:** download `OpenSteer-Setup-<version>.exe` and run it. It installs the
ViGEmBus driver if needed (that is what creates the virtual controller), then starts in the
system tray and shows a 6-digit code.

**Linux (x86-64):** download `OpenSteer-<version>-linux-x86_64.tar.gz`, then:

```sh
tar xzf OpenSteer-*-linux-x86_64.tar.gz
cd OpenSteer-*/
./install-linux.sh        # asks for sudo once, for access to /dev/uinput
```

Log out and back in, then start OpenSteer from your app menu.

## Pair your phone

Open **https://opensteer.web.app** on your phone (same Wi-Fi as the PC), sign in with Google,
tap **Pair with code**, and enter the code the PC app shows.

## Third-party software

The PC app bundles open-source components; their licenses are in `THIRD-PARTY-NOTICES.txt`
next to the installed app.
