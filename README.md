# Cisco DHCP Option 43 Generator (Wi-Fi 7 APs - FOM)

Cisco Wi-Fi 7 AP (CW917xシリーズ)向けのFast Offline Migration (FOM) 用DHCP Option 43のHEX値を生成します。

👉 GitHub Pages: https://myhomenwlab.github.io/Cisco_DHCP-Option-43_Generator_Wi-Fi7-FOM/

## 説明

* Cisco Wi-Fi 7 AP (CW917xシリーズ)がFast Offline Migration (FOM)を利用してCatalyst Mode (WLC Mode)またはMeraki Modeへ移行するためのDHCP Option 43を生成するツールです。
* 入力されたWLCのIPv4アドレスを元に16進数 (HEX)形式で出力します。
* Catalyst Mode (WLC Mode)ではWLCのIPv4アドレスが1台以上必要です。
* Meraki ModeではWLCのIPv4アドレスを指定せずにDHCP Option 43を生成できます。
* 本ツールはクライアント側のJavaScriptによって動作しており、外部のサーバーには送信を行いません。

## 関連ツール

* [Cisco DHCP Option 43 Generator (Wi-Fi 6E and Earlier APs)](https://myhomenwlab.github.io/Cisco_DHCP-Option-43_Generator_Wi-Fi6E_and_Earlier-APs/)
