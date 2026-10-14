# KNAS 42 for Samsung TVs

The [KNAS 42](https://github.com/thebust3r/KNAS42) cable box on a Samsung (Tizen) TV, full screen, with the whole remote working.

## Install with TizenBrew
1. On the TV, open **TizenBrew** → **Module Manager** → **Add** → **GitHub**.
2. Type `thebust3r/knas-samsung` and press OK.
3. Open **KNAS 42** and type your NAS's address (like `192.168.1.50`).

To change the address later, press the red **A** button while it says "Tuning in…".

## Install from a file (TizenBrew Installer, Device Manager)
Download **KNAS42.wgt** from the [Releases page](../../releases/latest) and install it with TizenBrew Installer (install from a file), Tizen Studio's Device Manager, or `tizen install -n KNAS42.wgt`. The TV needs Developer Mode on.

## Install with Tizen Studio
Import this folder as a Tizen project (File → Import → Tizen → Tizen Project), then right-click it → Run As → Tizen Web Application.
