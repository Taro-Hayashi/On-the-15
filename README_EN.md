# On the 15 Build Manual ([日本語](README.md))
- [Contents](#Contents)
- [Soldering](#Soldering)
- [Testing](#Testing)
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


### 追加できるもの
|部品名|||
|-|-|-|
|スタビライザー|2U、PCBマウント|[遊舎工房](https://shop.yushakobo.jp/collections/all-keyboard-parts/Stabilizer) / [TALPKEYBOARD](https://talpkeyboard.net/?category_id=5f884b9b3313d216eb50558a)|
|ロータリーエンコーダ|EC11/EC12/ロープロファイル|[遊舎工房](https://shop.yushakobo.jp/search?q=%E3%83%AD%E3%83%BC%E3%82%BF%E3%83%AA%E3%83%BC%E3%82%A8%E3%83%B3%E3%82%B3%E3%83%BC%E3%83%80%E3%83%BC+%E3%83%8E%E3%83%96%E4%BB%98%E3%81%8D) / [TALPKEYBOARD](https://talpkeyboard.net/items/5f3f1a597df28129f2fd4b0f) / [DailyCraftKeyboard](https://shop.dailycraft.jp/products/encoder_low) / [Amazon](https://www.amazon.co.jp/s?k=EC11+%E3%82%A8%E3%83%B3%E3%82%B3%E3%83%BC%E3%83%80%E3%83%BC&language=ja_JP)|
|ノブ|外径19mmまで|[DailyCraftKeyboard](https://shop.dailycraft.jp/products/encoder_lowprofile_knob) / [Amazon](https://www.amazon.co.jp/s?k=%E3%82%A8%E3%83%B3%E3%82%B3%E3%83%BC%E3%83%80%E3%83%BC+%E3%83%8E%E3%83%96)|

### 必要な工具
|工具名|
|-|
|はんだごて|
|こて先クリーナー（こて台）|
|鉛入りはんだ|
|ピンセット|
|精密ドライバー|


## レイアウトを決める
On the 15は60キーの格子配列キーボードですが、色のついたキーは長さを変更することができます。  
![](img/layout1.png)  

RemapやKeyboard Layout Editorでシミュレーションすることもできます。  
- [Remap - On the 15 - KEYMAP](https://remap-keys.app/catalog/9bQPDxdkX8xgflHlsR9p/keymap)
- [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/#/gists/feebeb1f95b04ed5593eb9c8289f1239)

ビルドガイドではこのようなレイアウトで組み立てます。　
![](img/layout2.png)  


## はんだ付け
### ソケットのはんだ付け
使うソケットのパッドに予備はんだをします。  
あらかじめ薄くはんだを乗せます。  
![](img/IMG_6124.JPEG)  
ソケットを置いたらピンセットで押さえつけながらはんだを注いでいきます。入り組んでいて表面積が多いので多めに必要になります。
![](img/IMG_6125.JPEG)  
最下段のキーはシルク印刷を参考にしてソケットを取り付けてください。
![](img/IMG_8033.jpg)  
慣れてきたら予備はんだを省略したり、一度に複数個置いてはんだ付けをすると楽になります。  
![](img/IMG_6126.JPEG)  
### リセットスイッチのはんだ付け
表面左側のRESETと書いてあるところにリセットスイッチを差して裏からはんだ付けします。  
![](img/IMG_6127.JPEG)  

### ロータリーエンコーダーのはんだ付け
足を折らないようにホールに通して裏からはんだ付けします。  
![](img/IMG_6128.JPEG)   

### 動作確認
キースイッチを差したり裏をピンセットで短絡したりして動作確認をしておくと安心です。  
![](img/IMG_6129.JPEG)   
![](img/IMG_6131.JPEG)   

## 組み立て
### スタビライザーを組み立てる
スタビライザーがあると2Uのキーの押下が安定します。無くても使えるのでお好みでお使いください。  
ねじ止め式のスタビライザーは縦に二つ並べておくことはできないので使う場所に気をつけるかスナップ型のスタビライザーを使ってください。  

小さい方のパーツの穴が二つ開いている側を、大きいパーツの穴が開いている方向に合わせて組み合わせます。  
![](img/IMG_4416.jpg)  
金属の棒を下の穴に差し込みツメにパチっと音がするまで押し込んで完成です。  
![](img/IMG_4420.jpg)    
基板の大きい方の穴にツメをひっかけながら取り付けます。  
![](img/IMG_6132.JPEG)  

### メインボードにトッププレートを取り付ける
トッププレートの裏側にスペーサーをねじ止めします。  
![](img/IMG_6149.JPEG)   
メインボードにかぶせて、4隅のスイッチをはめ込みます。  
![](img/IMG_6150.JPEG)   
すべてのスイッチを差し込みました。  
![](img/IMG_6152.JPEG)  

### アクリルプレートを挟み込む
画像のような形で3段にして挟み込みます。  
![](img/IMG_6161.JPEG)  
赤丸の部分の1段目は一度スペーサーを外してスライドさせた方が楽かもしれません。 
![](img/IMG_6159.JPEG)  


### バックプレートを取り付ける
バックプレートをねじ止めしてゴム足を貼ります。  
![](img/IMG_6153.JPEG)  
キーキャップを付けたら完成です。  
![](img/IMG_6154.JPEG)  
LEDをオフにしたい場合は左上(ESC)のキーを押しながらその下のキーを押してください。   
光り方を変えたい場合は左上(ESC)のキーを押しながらその隣のキーを押してください。  

## キーマップのカスタマイズ
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




## そのほか
### リセットスイッチの押し方
こちらの隙間からドライバーやピンセットを差し込むことで押すことができます。
![](img/IMG_6327.jpg)  
### 60%ケースに入れる
BOOTHにて60%ケース対応パーツをご購入いただくことでPoker互換ケースに入れることができます。
- [60%ケース対応パーツ ビルドガイド](60.md)

### ファームウェアのコード
https://github.com/Taro-Hayashi/qmk_firmware/tree/master/keyboards/tarohayashi/onthe15

### VIA用JSON
- [onthe15.json](https://github.com/Taro-Hayashi/On-the-15/releases/download/15.23/onthe15.json)

### プレートのデータ
- [onthe15_plates.zip](https://github.com/Taro-Hayashi/On-the-15/releases/download/15.23/onthe15_plates.zip)

### 販売ページ
- On the 15（BOOTH）: https://tarohayashi.booth.pm/items/3672079
