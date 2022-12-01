# robosys202x
## 概要
* このrobosys202xというリポジトリにはplusコマンド(これは足し算のコマンドです)が含まれる
* ロボットシステム学の練習用のリポジトリとして作成

## インストール方法
```
$ git clone https://github.com/shuma-300/robosys202x.git
$ cd robosys202x
```
を実行

## plusコマンド
![test](https://github.com/shuma-300/robosys202x/actions/workflows/test.yml/badge.svg)
* 標準入力から読み込んだ数字を足し、その合計を表示している。
## 実行例
```
$ seq 10 | ./plus
55
```
1から10までの数を足し、その合計を表示

## 必要なソフトウェア
* python 3.7 ~ 3.10
  * テスト済み

## 動作確認済み環境
* Ubuntu 22.04.1LTS

## 著作権とライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
```
https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022
```
* © 2022 Shuma Ito
