# On the 15 ビルドガイド（[English](README_EN.md)）
- [キット内容](#キット内容)
- [レイアウトを決める](#レイアウトを決める)
- [はんだ付け](#はんだ付け)
- [組み立て](#組み立て)
- [キーマップのカスタマイズ](#キーマップのカスタマイズ)
- [そのほか](#そのほか)

## キット内容
![](img/IMG_6331.jpg)  
![](img/IMG_8030.jpg)  
||部品名|数|
|-|-|-|
|1|メインボード|1|
|2|トッププレート|1|
|3|ボトムプレート|1|
|4|ネジ|22|
|5|スペーサー|11|
|6|リセットスイッチ|1|
|7|Cherry MX ホットスワップソケット|60|
|8|ゴム足|6|
|9|アクリルミドルプレート||
|10|2Uスタビライザー|1|
|11|ロータリーエンコーダー|1|
|12|ノブ|1|


### キット以外に必要なもの
|部品名|数|||
|-|-|-|-|
|キースイッチ|〜60|CherryMX互換|[遊舎工房](https://shop.yushakobo.jp/collections/all-switches/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81) / [TALPKEYBOARD](https://talpkeyboard.net/?category_id=59cf8860ed05e668db003f5d) / [DailyCraftKeyboard](https://shop.dailycraft.jp/collections/mx-switches)|
|キーキャップ|〜60|CherryMX互換|[遊舎工房](https://shop.yushakobo.jp/collections/keycaps/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%AD%E3%83%BC%E3%82%AD%E3%83%A3%E3%83%83%E3%83%97) / [TALPKEYBOARD](https://talpkeyboard.net/?category_id=59e2acfaed05e644fd004008)|
|Type-C ケーブル|1|||


### 追加できるもの
|部品名|||
|-|-|-|
|色違いアクリルプレート|-|[遊舎工房 - キーボードアクリルプレート](https://shop.yushakobo.jp/collections/services/products/keyboard_acrylic_plate?variant=43949129629927)|
|スタビライザー|2U、PCBマウント|[遊舎工房](https://shop.yushakobo.jp/collections/all-keyboard-parts/Stabilizer) / [TALPKEYBOARD](https://talpkeyboard.net/?category_id=5f884b9b3313d216eb50558a)|
|ロータリーエンコーダ|EC11/EC12/ロープロファイル|[遊舎工房](https://shop.yushakobo.jp/search?q=%E3%83%AD%E3%83%BC%E3%82%BF%E3%83%AA%E3%83%BC%E3%82%A8%E3%83%B3%E3%82%B3%E3%83%BC%E3%83%80%E3%83%BC+%E3%83%8E%E3%83%96%E4%BB%98%E3%81%8D) / [TALPKEYBOARD](https://talpkeyboard.net/items/5f3f1a597df28129f2fd4b0f) / [DailyCraftKeyboard](https://shop.dailycraft.jp/products/encoder_low)|
|ノブ|外径19mmまで|[遊舎工房](https://shop.yushakobo.jp/products/3733) / [DailyCraftKeyboard](https://shop.dailycraft.jp/products/encoder_lowprofile_knob)|

専用のアクリルケースもあります。  
- [On the 15 アクリル積層ガスケットマウントケース](https://github.com/Taro-Hayashi/On-the-15-AcrylicCase/blob/main/README.md)  


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

ビルドガイドではこのようなレイアウトで組み立てます。　
![](img/layout2.png)  


## はんだ付け
### ソケットのはんだ付け
使うソケットのパッドに予備はんだをします。  
あらかじめ薄くはんだを乗せます。  
![](img/IMG_6124.JPEG)  
ソケットを置いたらピンセットで押さえつけながらはんだを注いでいきます。入り組んでいて表面積が多いので多めに必要になります。
![](img/IMG_6125.JPEG)
慣れてきたら予備はんだを省略したり、一度に複数個置いてはんだ付けをすると楽になります。  
![](img/IMG_6126.JPEG)  
### リセットスイッチのはんだ付け
表面左側のRESETと書いてあるところにリセットスイッチを差して裏からはんだ付けします。  
![](img/IMG_6127.JPEG)  

### ロータリーエンコーダーのはんだ付け
足を折らないようにホールに通して裏からはんだ付けします。  
![](img/IMG_6128.JPEG)   

### テストファームウェアの書き込み
テスト用のファームウェアをこちらからダウンロードしてください。
- https://remap-keys.app/catalog/9bQPDxdkX8xgflHlsR9p/firmware

![](img/firmwaretest.png) 

QMK Toolboxのreleaseページから最新版をダウンロードしてインストールください。  
- [Releases・qmk/qmk_toolbox](https://github.com/qmk/qmk_toolbox/releases)

![](img/release.png)  
起動したらOpenを押してダウンロードしたファームウェアを指定し、はんだ付けしたリセットボタンを押します。  
![](img/qmktoolbox1.png)   
新しく黄色の文字が出てきたらFlashを押します。  
![](img/qmktoolbox2.png)  

Thank youの後に黄色い文字が出たら更新完了です。  
![](img/qmktoolbox3.png)   

### 動作確認
キースイッチを差したり裏をピンセットで短絡したりして動作確認をします。  
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

### バックプレートを取り付ける
バックプレートをねじ止めしてゴム足を貼ります。  
![](img/IMG_6153.JPEG)  
キーキャップを付けたら完成です。  
![](img/IMG_6154.JPEG)  

### Remap用ファームウェアの書き込み
Remap用のファームウェアをこちらからダウンロードして、さきほどと同様に書き込んでください。
- https://remap-keys.app/catalog/9bQPDxdkX8xgflHlsR9p/firmware

![](img/firmwareremap.png)

## キーのカスタマイズ
こちらのサイトにアクセスしてください。
- Remap https://remap-keys.app

![](img/remap1.png)  
左を選んで進んでいくとダイアログが出てキーボードを選択できます。  
![](img/remap2.png)  
選択して接続してください。
![](img/remap3.png)  

### キーマップの保存と復元
⇔アイコンで作ったキーマップを保存することができます。  
![](img/remapkey.png)  
作ったキーマップを共有することもできるので是非お試しください。

### レイアウトを変える
キーボードの右のこのボタンでレイアウトを変えることができます。  
![](img/remaplayout.png)  

### キーを設定する
下のキー一覧からドラッグアンドドロップし、変更が終わったら右上のflashボタンを押すと反映されます。  
![](img/remapflash.png)  
また、USキーボードとJISキーボードはFlashの下のプルダウンから変更できます。OSの設定に合わせてください。

### 修飾キーとの組み合わせを設定する
上のキーボードのキーをクリックすると設定画面になります。
![](img/remapmod1.png)  
修飾キーと同時押ししたいキーを検索し、同時押ししたい修飾キーにチェックを入れます。
![](img/remapmod2.png)  

Hold-Tapもここから設定できます。

### ロータリーエンコーダーを設定する
丸いキーの左下をクリックすると時計回り、反時計回りを切り替えることができるので、それぞれにキーを割り当てます。
![](img/remapenc.png)  

### 特殊なキーを設定する
FUNCTIONSタブのVIA USER KEYにあらかじめ用意されたショートカットキーがあります。
![](img/remapshortcuts.png)  

### LEDを調整する
このボタンで発光方法を変更することができます。
![](img/remapledset.png)  

## そのほか
### リセットスイッチの押し方
こちらの隙間からドライバーやピンセットを差し込むことで押すことができます。
![](img/IMG_6327.jpg)  

### ファームウェアのコード
https://github.com/Taro-Hayashi/qmk_firmware/tree/tarohayashi/keyboards/tarohayashi/onthe15

### プレートのデータ
- [onthe15_plates.zip](https://github.com/Taro-Hayashi/On-the-15/releases/latest/download/onthe15_plates.zip)

### 販売ページ
- 遊舎工房: [On the 15](https://shop.yushakobo.jp/products/4994?variant=43917315539175)
- BOOTH: [On the 15（B-Stock）、アクリルケース](https://tarohayashi.booth.pm/items/3672079)

