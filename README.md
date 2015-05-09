# tokotika.rb

トコチカはTOCOS Wireless（東京コスモス電機）が提供するToCoStickから TWE-Liteを操作してLEDを点滅させるためのRubyスクリプトです。

http://tocos-wireless.com/jp/products/TWE-Lite-USB/control.html

ArduinoのanalogWrite関数と同じく analogWrite(ピン番号、値０〜１０２４） で制御可能です。

# 動作環境

筆者は下記の環境で動作確認しています。

MacOS 10.10.3
Ruby 2.0.0
serialport 1.3.1
