# LocalOrders POS for Windows — releases

Installers and auto-update feeds for the LocalOrders POS for Windows till.
Published automatically by the private source repo's `Release` workflow on
each version tag. **There is no source code here.**

| Channel | Who | Feed file |
| --- | --- | --- |
| production | venues | `latest.yml` + `LocalOrders POS-Setup-<version>.exe` |
| staging | testers | `staging.yml` + `LocalOrders POS-STAGING-Setup-<version>.exe` |

Installed apps check this repo at launch and every four hours, download the
next version silently, and install it at 04:00 local time. A staging install
follows the staging channel only, and a production install the production
channel only.

Download the installer for your channel from the latest release's assets.
