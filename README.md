## ros2

![test](https://github.com/Ohashi822/mypkg/actions/workflows/test.yml/badge.svg)

## このレポジトリについて
* このソフトウェアパッケージは,ロボットシステム学を学習するためのものである．

* このソフトウェアパッケージでは,二つの端末を用いることで,ROS2でのパブリッシャーとサブスクライバーの通信を確認することができる．

## ROS2のインストール方法  
```
$ git clone https://github.com/ryuichiueda/ros2_setup_scripts
$ cd ros2_setup_scripts
$ ./setup.bash
$ source ~/.bashrc
```

## このパッケージのインストール方法
```
$ git clone https://github.com/Ohashi822/mypkg.git
```
## このパッケージの使用方法
 * 端末1
 ```
 $ ros2 run mypkg talker 
 ```
 * 端末2
 ```
 $ ros2 run mypkg listener
 ```

## 必要なソフトウェア
* Python 3.7 ～ 3.10

* Ubuntu22.04では動作確認済み.

## ライセンス
* このソフトウェアパッケージは,3条項BSDライセンスの下,再配布および使用が許可される.

* このパッケージのコードは下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを,本人の許可を得て自著作としたものである.
  * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

* © 2022 Kazuma Ohashi
