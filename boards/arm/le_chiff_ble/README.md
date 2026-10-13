# Le_Chiff_BLE

自定义主控（自定义 PCB，nRF52840 QIAA）。板定义已迁移到 Zephyr 4.x 新栈规范
（`board.yml` + `Kconfig.le_chiff_ble`，见 [Zephyr Board Porting 文档](https://docs.zephyrproject.org/latest/hardware/porting/board_porting.html)）。

## Building Le_Chiff_BLE ZMK firmware
```
west build -p -b le_chiff_ble -- -DSHIELD="nice_view_adapter nice_view"
```

更推荐在仓库根目录通过 GitHub Actions 构建（`build.yaml` 已配置
`board: le_chiff_ble` + `shield: nice_view_adapter nice_view` + DYA Studio snippet）。
