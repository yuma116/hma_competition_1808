# General Rules
* 本競技会では，Aチームは「TurtleBot3 1号機」を，Bチームは「TurtleBot3 4号機」を使用するものとする
* Webカメラは，運営が各チーム1台ずつ貸し出すので，そちらをロボットに搭載すること
  * ロボットへの搭載は各チームが行う
* 外部コンピュータとして，運営が講習中に貸し出しているathomeまたはcarroboの番号が振られたパソコンを使用すること
  * そのうち，どのパソコンを使用しても良い
* 運営はWiFiネットワークを用意しないため，利用する場合は各チームが独自に準備をすること
* ロボットとパソコンの接続は，支給されたLANケーブルを用いて行うこと

# Navigation and Follow Challenge

## Focus
* 既知環境でのナビゲーション
* オペレータの追跡

## Setup
* **Arina**
  * 机の上に，1[m]四方サイズの「Arina」が用意される．
  * Arina内には，1つのDoorと，いくつかの家具（障害物）が設置される．
  * また，Arina中には「Start Position」「Navigation Goal」「Follow Person Goal」が設置される．
  * Arinaと，Doorと家具の設置場所，「Start Position」「Navigation Goal」はSetupDayに公開される．

* **Start Position**
  * スタート時，ロボットはアリーナ内で指定される「Start Position」に設置される．
  * ロボットの正面には「Door」が用意される．
  * Start PositionはSetupDayに公開される．

* **Door**
  * アリーナ内に「Door」は1つだけ設置される．
  * Doorは全体が赤色で着色されている．
  * DoorはSetupDayに公開される．

* **Navigation Goal**
  * アリーナ内では「Navigation Goal」と呼ばれる場所が1箇所定義される．
  * 「Navigation Goal」はSetupDayに公開される．

* **Follow Person Goal**
  * アリーナ内では「Follow Person Goal」と呼ばれる場所が3箇所定義される．
  * 「Follow Person Goal」はSetupDayに公開される．

* **Operator**
  * 本ルールでは，全チームが「Custom Operator」を用意する必要がある．

## Task
* **Start**
  * ロボットの正面のドアがオープンするまで，ロボットはその場に留まらなければならない．
  * ドアがオープンすると，ロボットは移動を開始することができる．

* **Navigation Phase**
  * ロボットは自律的に「Navigation Goal」へ向かう．
  * Navigation Goal へ到着したロボットは，その場で停止する．

* **Follow Person Phase**
  * ロボットは「Custom Operator」の誘導に従い，Navigation Goalから移動する．
  * 目的地として，事前定義された3箇所の「Follow Person Goal」からランダムに1箇所が指定される．

## Score Sheet
* タスクの制限時間は10分である．
* 競技は3トライアル実施し，点数の良い2トライアルの平均を最終的な得点とする

|Action                                                                |Score|
| :-                                                                   |   -:|
|                                                                      |     |
|***Start***                                                           |     |
|	Doorのオープンを認識し，Start Positionから移動することができた       |   10|
|***Navigation Phase:***                                               |     |
|	Navigation Goal へ到着し，停止することができた				               |   10|
|***Follow Person Phase:***                                            |     |
|	Follow Person Goal へ到着し，停止することができた				             |   10|
|***Special penaltie:***	                                             |     |
|　Not attending					                                             |  -50|
|                                                                      |     |
|合計(penaltiesとbonusを除いて)                                        |   30|
