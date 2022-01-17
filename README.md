# robosys＿課題2
2021年度ロボットシステム学の課題2です。
以下のscriptsを実行させ、時間経過ごとの数値を確認します。

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
 実行する
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
 実行する
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
 実行する
 ```
rosrun mypkg third.py
 ```
 実行中の内容を確認する
 ```
rostopic echo /third
 ```
# デモ動画

https://youtu.be/ILBf_BQGses

# ライセンス
Copyright (c) 2022 Ryuichi Ueda

Copyright (c) 2022 Douseki Tei

ライセンス：[LISENCE](https://github.com/Douseki-Tei/mypkg/blob/main/LICENSE)
