## Download and Install

### Direct Downloads
Windows latest (zip file-windows 11 alll versions):
https://github.com/HovSaintBrandon/VenueFY-for-JKUAT-/releases/download/App-distro/VenueFY.zip

Linux (Latest `.deb` or `.rpm`):
[https://github.com/HovSaintBrandon/VenueFY-for-JKUAT-/releases/latest](https://github.com/HovSaintBrandon/VenueFY-for-JKUAT-/releases/download/App-distro/VenueFY-v1.0.0_amd64.deb))

Android APK (Latest release):
[https://github.com/HovSaintBrandon/VenueFY-for-JKUAT-/releases/latest](https://github.com/HovSaintBrandon/VenueFY-for-JKUAT-/releases/download/App-distro/VenueFY-3.2.0.apk))

### Option 1. GUI install

1. Open the Releases page.
   [https://github.com/HovSaintBrandon/VenueFY-for-JKUAT-/releases/latest](https://github.com/HovSaintBrandon/VenueFY-for-JKUAT-/releases/latest)

2. Download the file for your system.

   * Ubuntu, Debian, Linux Mint, Pop!_OS, Zorin, elementary: `VenueFY-vX.X.X_amd64.deb`
   * Fedora, Rocky Linux, AlmaLinux, CentOS, RHEL: `VenueFY-vX.X.X-1.x86_64.rpm`
   * openSUSE: use the `.rpm`
   * Arch and Manjaro: use the `.deb` with debtap or extract it
   * Android: download the `.apk`

3. Double click the file.
   Install through the system installer.
   VenueFY appears in your menu.

### Option 2. Terminal install

```bash
# Ubuntu, Debian, Mint, Pop_OS, Zorin
sudo dpkg -i VenueFY-v*.deb
sudo apt install -f

# Fedora, RHEL, AlmaLinux, Rocky, CentOS
sudo dnf install VenueFY-v*-1.x86_64.rpm

# openSUSE
sudo zypper install VenueFY-v*-1.x86_64.rpm

# Arch or Manjaro
yay -S debtap
sudo debtap -u
sudo debtap VenueFY-v*.deb
sudo pacman -U *.pkg.tar.zst
```

## Launch the app

```bash
venuefy
```

Or search for VenueFY in your menu.

## Uninstall

```bash
# Debian based
sudo apt remove venuefy

# Fedora, RHEL, openSUSE
sudo dnf remove venuefy
# or
sudo zypper remove venuefy
```

VenueFY installs with one click. No build tools or SDKs required.
