# COPYING
(c) 2020 RyuichiUeda and kaitoyamazaki　and yuyakobayashi7 and note032 and rikusekiuchi

# robosys_device_driver
ロボットシステム学の課題で作ったものです。 LEDを点灯、消灯、点滅するデバイスドライバーを作成しました。

# 実行方法
    $ git clone 
    $ cd robosys_device_driver
    $ make
    $ sudo insmod myled.ko
    $ sudo chmod 666 /dev/myled0
    

# 映像
ここにYouTubeのリンク

# 説明
echo 0 > /dev/myled0    全てのLEDを消す。

echo 1 > /dev/myled0    全てのLEDを光らせる。

echo 2 > /dev/myled0    1つ目のLEDを光らせる

echo 3 > /dev/myled0    2つ目のLEDを光らせる

echo 4 > /dev/myled0    2つ目のLEDを間隔が短くなるよう点滅させる

echo 5 > /dev/myled0    1つ目のLEDを一定間隔で点滅させる

echo 6 > /dev/myled0    2つのLEDを交互に点滅させる

# 写真
回路の写真を貼ろう
# LICENSE
This repository is licensed under the GPLv3 license

# References
https://github.com/rikusekiuchi/led_devicce_driver_2
https://github.com/note032/test_report
複数のGPIO制御と、LEDの点滅に一部コードを使用しています。

https://github.com/yuyakobayashi7/robosys_device_driver
READMEの記入に一部コードを使用しています。
