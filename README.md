### Run adb and fastboot in Termux without root permissions!

**official** [Repo](https://github.com/nohajc/termux-adb) **by:** [nohajc](https://github.com/nohajc)

<sub>**changes**: Include improving install and creating symbolic links: termux-adb ➜ adb, termux-fastboot ➜ fastboot</sub>

### Installation

1. Install [Termux](https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_universal.apk)

2. Install [Termux API](https://github.com/termux/termux-api/releases/download/v0.50.1/termux-api_v0.50.1+github-debug.apk)

3. From Termux command line:
```bash
curl -s https://raw.githubusercontent.com/offici5l/termux-adb-fastboot/main/install | bash
```
Or
```bash
curl -s https://raw.githubusercontent.com/offici5l/termux-adb-fastboot/test/utermuxadb | bash
```