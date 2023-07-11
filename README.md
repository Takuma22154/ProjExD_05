# 学長が転んだ
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
キャラクターを操作し障害物や学長の目を避けながら馬に乗ることを目指すゲーム

## ゲームの実装
###共通基本機能
* 背景画像表示
### 担当追加機能
* 操作キャラクタークラス：キー入力によりキャラクターを操作するためクラス(character)
* 障害物クラス：マップ内に障害物を表示させるクラス(enemy)
* 学長クラス：学長に関するクラス(gakucho)
* 遮蔽物クラス：学長の目から逃れるための遮蔽物に関するクラス(wall)
* メニュークラス：スタートメニューに関するクラス(menu)
* 背景クラス：背景と地面に関するクラス(background)
### ToDo
* Characterクラスに追加機能実装

### メモ

