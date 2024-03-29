<div align="center">
  <img src="sample/icon.ico" alt="Logo" width="100" height="100">
  <h3 align="center">YUV-Observer.exe</h3>
  <p align="center">
    A simple YUV file viewer for Windows 10 System.<br />
    Windows 10で動作する簡易的YUVファイルビュアーソフト
    <br />
    Latest version: v0.1.1.0
    <br />
    <br />
    <br />
  </p>
</div>

本ソフトのダウンロードはこちらの[リンク](https://github.com/7ra4no/YUV-Observer/releases)から

Assetsのプルダウンより`YUV-Observer.zip`をダウンロードしてください

注意事項をよく読みご利用ください

## 機能

* YUV444，YUV422，YUV420，YUV400の表示，それらのPNGファイル書き出し
* 閲覧するYUV形式画像のYUVレイヤーとRGBレイヤーの分離表示
* 閲覧するYUV画像の拡大縮小ビュー（試験的機能のためメモリ不具合あり）


## 読み込むYUVファイルの名前

* 任意のファイル名であっても縦横サイズ，YUV形式の種類を正しく入力することで表示が可能
* また，以下の形式のファイル名であるならばそのまま開くことが可能

```sh
hogehoge(1024x768,YUV444).yuv
```

もしくは

```sh
fugafuga(1024x768_444).yuv
```

## 動作例

### YUV-Observer.exe 動作デモ
<div align="center">
<img src="sample/yuvdemo.gif" alt="YUV444" width="300" height=""></br>
</div>

### YUV444(4:4:4)
<div align="center">
<img src="sample/yuv444.png" alt="YUV444"></br>
</div>

### YUV422(4:2:2)
<div align="center">
<img src="sample/yuv422.png" alt="YUV422"></br>
</div>

### YUV420(4:2:0)
<div align="center">
<img src="sample/yuv420.png" alt="YUV420"></br>
</div>

### RGB
<div align="center">
<img src="sample/rgb.png" alt="RGB"></br>
</div>

## ライセンス

Distributed under the 3-clause BSD License. See `LICENSE.txt` for more information.


## 使用ライブラリ

* [NumPy](https://numpy.org/)
* [OpenCV](https://opencv.org/)


## 謝辞

このプログラムの制作にあたり，以下のサイト様より知見をいただきました．ここで改めて感謝いたします．問題などがございましたら対処いたしますのでご連絡ください．

* [その他の画像変換 — opencv 2.2 documentation](http://opencv.jp/opencv-2svn/c/miscellaneous_image_transformations.html)
* [Recommended 8-Bit YUV Formats for Video Rendering - Win32 apps](https://docs.microsoft.com/en-us/windows/win32/medfound/recommended-8-bit-yuv-formats-for-video-rendering)
* [BT.601 BT.709 BT.2020 BT.2100規格 - 虹色の旋律](http://nijikarasu.cocolog-nifty.com/blog/2017/08/bt601-bt709-bt2.html)
* [RGBからYCbCrへ変換する際の注意 - 虹色の旋律](http://nijikarasu.cocolog-nifty.com/blog/2020/02/post-3c4fbe.html)
* [JPEG のクロマサブサンプリングと YUVabc](http://blog.awm.jp/2016/02/10/yuv/)
* [YUVをちゃんと理解してからRGBにコンバートしましょうね](https://www.klab.com/jp/blog/tech/2016/1054828175.html)
* [YUVフォーマット及び YUVとRGBの変換](https://hk.interaction-lab.org/firewire/yuv.html#packed_format)
* [Processing YUV I420 from framebuffer?](https://stackoverflow.com/questions/69518644/processing-yuv-i420-from-framebuffer)
