# Talos Linux for Rockchip Boards (Rock 5 ITX, Rock 5B, …)

**Automated Talos Linux builds for Rockchip RK3588 boards with Google Coral TPU support.**

## 🚀 Installation
1. Download the latest release from [GitHub Releases](https://github.com/xhochn/talos-rock/releases).
2. Write the image to an SD card or eMMC:
   ```sh
   dd if=talos-rock5b.img of=/dev/sdX bs=4M status=progress
   sync
