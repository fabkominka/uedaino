# オリジナルArduinoを作る



## 仕様を決める
- 仕様
  - 電源
  - 単体での書き込み機能
  - 端子
  - 外形、シルク
- 製造方針
  - 基板は何層にするか
  - 部品実装は手ハンダかリフローか



### 電気仕様を決める


#### Arduino Unoの機能を確認する
- [Overview](https://store-usa.arduino.cc/products/a000066)
- [回路図](https://www.arduino.cc/en/uploads/Main/Arduino_Uno_Rev3-schematic.pdf)
- CPUのデータシート [Atmega 328p](http://www.atmel.com/images/atmel-8271-8-bit-avr-microcontroller-atmega48a-48pa-88a-88pa-168a-168pa-328-328p_datasheet_complete.pdf)


#### Overview


#### 回路図


#### CPU



### 外形仕様を決める
- ケースの寸法
- 基板の値段を考慮する
- ネジ穴



## 回路図を描く


### 回路図、基板レイアウトエディタ
- Fritzing
- KiCad
- Eagle
- DesignSpark PCB (Winのみ)


### レイアウト
- 実装方針に合わせて部品の選定



## 部品を選定する
- 大手のサイト、もしくは身近な場所でで購入できるものにする
  - digikey
  - mouser
  - 秋月電子
  - 千石電商
  - aitendo
- 表面実装部品かスルーホール部品か
- リフローできる部品か



## 製造する
- オンラインでオーダーできるPCB製造サービスがいくつもある


### 基板をオーダーする
- 中国のサービスが安い
  - [Fusion PCB](https://www.seeedstudio.com/fusion_pcb.html)
  - [Elecrow](http://www.elecrow.com)
- 実装サービスもある


#### Gerberデータ
- 製造用のデータ
  - シルク
  - レジスト
  - パターン
  - 外形
  - ドリル


#### BOMを作る
BOM(Bill of Materials)



## 実装する


### オーブントースターリフロー




