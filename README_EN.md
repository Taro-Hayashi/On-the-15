# On the 15 Build Manual ([日本語](README.md))
- [Contens](#Contens)
- [Preparation](#Preparation)
- [Soldering](#Soldering)
- [Assembling](#Assembling)
- [Customise](#Customise)

## Contents
![](img/IMG_6331.jpg)  
![](img/IMG_8030.jpg)  
||Name|Quantities|
|-|-|-|
|1|Main board|1|
|2|Top plate|1|
|3|Bottom plate|1|
|4|Screws|22|
|5|Spacers|11|
|6|Tactile Switch|1|
|7|Hotswap sockets|60|
|8|Rubber feet|6|
|9|Middle paltes||
|10|Stabilizer|1|
|11|Rotary encoder|1|
|12|Knob|1|


### Additional required
|Name|Quantities||
|-|-|-|
|Keyswitches|up to 60|CherryMX|
|Keycaps|up to 60|CherryMX|
|Type-C Cable|1||


### Optional
|Name||
|-|-|
|Stabilizer|2U, PCB mounted|
|Rotary encoders|EC11/EC12|
|Knobs|Outer diameter up to 19mm|


## Preparation
This kit has a variety of layouts to choose from.
![](img/layout1.png)    
- [Remap - On the 15 - KEYMAP](https://remap-keys.app/catalog/9bQPDxdkX8xgflHlsR9p/keymap)
- [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/#/gists/feebeb1f95b04ed5593eb9c8289f1239)

In this manual, we use rotary encoder and 2 2U keys.
![](img/layout2.png)  


## Soldering
### Hotswap sockets
使うソケットのパッドに予備はんだをします。  
あらかじめ薄くはんだを乗せます。  
![](img/IMG_6124.JPEG)  
ソケットを置いたらピンセットで押さえつけながらはんだを注いでいきます。入り組んでいて表面積が多いので多めに必要になります。
![](img/IMG_6125.JPEG)  
最下段のキーはシルク印刷を参考にしてソケットを取り付けてください。
![](img/IMG_8033.jpg)  
慣れてきたら予備はんだを省略したり、一度に複数個置いてはんだ付けをすると楽になります。  
![](img/IMG_6126.JPEG)  
### Tactile switch
表面左側のRESETと書いてあるところにリセットスイッチを差して裏からはんだ付けします。  
![](img/IMG_6127.JPEG)  

### Rotary encoder
足を折らないようにホールに通して裏からはんだ付けします。  
![](img/IMG_6128.JPEG)   

### Testing
キースイッチを差したり裏をピンセットで短絡したりして動作確認をしておくと安心です。  
![](img/IMG_6129.JPEG)   
![](img/IMG_6131.JPEG)   

## Assembling
### Stabilizers
スタビライザーがあると2Uのキーの押下が安定します。無くても使えるのでお好みでお使いください。  
ねじ止め式のスタビライザーは縦に二つ並べておくことはできないので使う場所に気をつけるかスナップ型のスタビライザーを使ってください。  

小さい方のパーツの穴が二つ開いている側を、大きいパーツの穴が開いている方向に合わせて組み合わせます。  
![](img/IMG_4416.jpg)  
金属の棒を下の穴に差し込みツメにパチっと音がするまで押し込んで完成です。  
![](img/IMG_4420.jpg)    
基板の大きい方の穴にツメをひっかけながら取り付けます。  
![](img/IMG_6132.JPEG)  

### Plates
トッププレートの裏側にスペーサーをねじ止めします。  
![](img/IMG_6149.JPEG)   
メインボードにかぶせて、4隅のスイッチをはめ込みます。  
![](img/IMG_6150.JPEG)   
すべてのスイッチを差し込みました。  
![](img/IMG_6152.JPEG)  
画像のような形で3段にして挟み込みます。  
![](img/IMG_6161.JPEG)  
赤丸の部分の1段目は一度スペーサーを外してスライドさせた方が楽かもしれません。 
![](img/IMG_6159.JPEG)  
バックプレートをねじ止めしてゴム足を貼ります。  
![](img/IMG_6153.JPEG)  
キーキャップを付けたら完成です。  
![](img/IMG_6154.JPEG)  
LEDをオフにしたい場合は左上(ESC)のキーを押しながらその下のキーを押してください。   
光り方を変えたい場合は左上(ESC)のキーを押しながらその隣のキーを押してください。  

## Customise
デフォルトではビルドガイドに合わせたキーマップになっています。
![](img/layout3.png)
ChromeかEdgeでRemapにアクセスしてください。  
- Remap https://remap-keys.app/


![](img/remap1.png)  
左を選んで進んでいくとアドレスバーからメッセージが出てキーボードを選択できます。  


ドラッグアンドドロップでキーマップの変更が終わったら右上のflashボタンを押すと反映されます。  
![](img/remap2.png)  

### レイアウトオプション
キーの長さを作ったキーボードと合わせることができます。
![](img/layoutoption.png)  
### レイアウトの保存と復元
⇔アイコンで作ったレイアウトを保存することができます。  
![](img/keymaps.png)  
いくつかサンプルをご用意しました。自分のレイアウトを公開することもできますのでお気軽に共有してください。

### Repository
https://github.com/Taro-Hayashi/qmk_firmware/tree/master/keyboards/tarohayashi/onthe15

### JSON
- [onthe15.json](https://github.com/Taro-Hayashi/On-the-15/releases/download/15.23/onthe15.json)

### Plates data
- [onthe15_plates.zip](https://github.com/Taro-Hayashi/On-the-15/releases/download/15.23/onthe15_plates.zip)

- On the 15（BOOTH）: https://tarohayashi.booth.pm/items/3672079
