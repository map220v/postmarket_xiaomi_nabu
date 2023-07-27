# postmarket_xiaomi_nabu
PostmarketOS for Xiaomi Pad 5

## Works
- Audio
- USB Gadget mode
- Display (novatek,nt36523)
- GPU (FD640)
- Wifi
- Bluetooth
- CPU (tlmm, clock controllers)
- UFS Storage
- IOMMU
- Touchscreen (nt36523 ts-spi)
- Thermal sensors
## Broken
- 6.2 - 6.5-rc2 unstable, ufs and dsi clocks can be stuck in disabled state.
- Accelerometer & Gyroscope (lsm6dso)
