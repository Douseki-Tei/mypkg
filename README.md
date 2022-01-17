# robosys＿課題2
2021年度ロボットシステム学の課題2です。


# 動作環境
Ubuntu20.04

Raspberry Pi 4

# 実行

Ubuntuを3つ立ち上げておく
---

## count.pyを立ち上げる

最初にロスコアを立ち上げる
 ```
roscore &
 ```
 ```
chmod +x count.py
 ```
  ```
source ~/.bashrc
 ```
 実行
 ```
rosrun mypkg count.py
 ```
 実行中の内容を確認する
 ```
rostopic echo /count_up
 ```
## twice.pyを立ち上げる
  ```
chmod +x twice.py
 ```
  ```
source ~/.bashrc
 ```
 実行
 ```
rosrun mypkg twice.py
 ```
 実行中の内容を確認する
 ```
rostopic echo /twice
 ```
## third.pyを立ち上げる
  ```
chmod +x third.py
 ```
  ```
source ~/.bashrc
 ```
 実行
 ```
rosrun mypkg third.py
 ```
 実行中の内容を確認する
 ```
rostopic echo /third
 ```
# デモ動画

https://youtu.be/lh7DT14W15o

# ライセンス
Copyright (c) 2022 Ryuichi Ueda

Copyright (c) 2022 Douseki Tei

ライセンスについて：[LISENCE](https://github.com/hiro2001/mypkg/blob/main/LICENSE)
