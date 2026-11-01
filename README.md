# OpenSteer

Use your phone as a racing wheel or a gamepad for PC games. The phone tilts like a steering
wheel (or shows pedals, buttons and sticks); the PC sees an Xbox 360 or DualShock 4 controller.

This repository hosts the **PC app downloads**. Get the latest version from
[Releases](https://github.com/tahabasegmez/open-steer/releases/latest).

## Install

**Windows 10 / 11:** download `OpenSteer-Setup-<version>.exe` and run it. The installer isn't
code-signed yet, so Windows may say it protected your PC: click **More info**, then **Run anyway**.
It installs the
ViGEmBus driver if needed (that is what creates the virtual controller), then starts in the
system tray and shows a pairing code with a QR code.

**Linux (x86-64):** download `OpenSteer-<version>-linux-x86_64.tar.gz`, then:

```sh
tar xzf OpenSteer-*-linux-x86_64.tar.gz
cd OpenSteer-*/
./install-linux.sh        # asks for sudo once, for access to /dev/uinput
```

Log out and back in, then start OpenSteer from your app menu.

## Pair your phone

Scan the QR code in the PC app's window with your phone's camera, or open
**https://opensteer.web.app** on your phone, sign in with Google, tap **Pair with code**, and type
the code the PC app shows.

## License

OpenSteer is free to use. See [LICENSE](LICENSE).

## Third-party software

The PC app bundles open-source components; their licenses are in `THIRD-PARTY-NOTICES.txt`
next to the installed app.
