# USART 助手

一款專為開發者與工程師設計的專業串口通訊工具。這款全方位 UART/USART 調試助手，提供即時監控、數據分析與串口通訊控制功能。

## 主要特點

### 串口通訊
- 支援多埠自動偵測
- 可配置鮑率（300 至 921600）
- 支援多種數據格式（5-8 位元、校驗、停止位）
- 流控選項（無、RTS/CTS、XON/XOFF）

### 數據顯示與分析
- 雙模式顯示（ASCII/HEX）
- 即時數據監控
- 時間戳顯示
- 自動滾動選項
- 多格式數據選取與複製

### 進階工具
- RS232 線路狀態監控
  - RTS/DTR 控制
  - CTS/DSR/CD/RI 狀態指示
- 校驗和計算器
  - 多種演算法（CRC16、CRC8、XOR 等）
- 進位轉換器
  - 二進位、八進位、十進位、十六進位
- 快速發送按鈕
  - 可自定義指令
  - 預設配置

### 使用者體驗
- 現代化直觀介面
- 可配置顯示選項
- 數據日誌記錄功能
- 可自定義快速發送按鈕
- 自動儲存設定

### 多組態支援
- 根據執行檔名稱自動管理設定檔
- 不同使用場景獨立設定
- 自動儲存與載入配置
- 保留多組通訊設定
- 輕鬆切換不同配置

範例：


```
usart_assistant.exe -> usart_assistant.json (Default settings)
pusart_assistant.exe -> pusart_assistant.json (Power supply communication)
mreader_assistant.exe -> mreader_assistant.json (RFID reader settings)
```



## 系統需求
- Windows 10 64 位元或更新版本

## 安裝方式
1. 下載最新版本
2. 執行安裝程式
3. 啟動 USART 助手

## 截圖

![](https://raw.githubusercontent.com/danny-source/USART_Assistant/refs/heads/main/screenshot/com.png)

![](https://raw.githubusercontent.com/danny-source/USART_Assistant/refs/heads/main/screenshot/receive.png)

![](https://raw.githubusercontent.com/danny-source/USART_Assistant/refs/heads/main/screenshot/transmit.png)

![](https://raw.githubusercontent.com/danny-source/USART_Assistant/refs/heads/main/screenshot/conveter.png)

![](https://raw.githubusercontent.com/danny-source/USART_Assistant/refs/heads/main/screenshot/calculator.png)

## 贊助支持

[![使用 PayPal 贊助](https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png)](https://www.paypal.me/dannytwdanny)

## Download

[USART_Assistant](https://github.com/danny-source/USART_Assistant/tree/main)