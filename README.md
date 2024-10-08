# RPi-4Relay-Control

## 專案簡介
`RPi-4Relay-Control` 是一個 Raspberry Pi 的 4 通道繼電器控制與狀態記錄系統。此專案允許使用者透過 GPIO 接腳控制 4 個繼電器的狀態，並將每次的輸入和對應的輸出狀態記錄到 CSV 檔案中。此系統可以用來進行設備控制或監控，並保留歷史日誌。

## 功能
- 控制 4 通道繼電器，使用 Raspberry Pi 的 GPIO 接腳進行輸入控制。
- 讀取每個繼電器的狀態（輸出）。
- 自動生成 CSV 檔案，記錄每次操作的日期、時間、輸入值及對應的繼電器輸出狀態。
- 支援以 4 位數的二進位形式輸入開關狀態。
