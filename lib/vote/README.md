# 投票のモデル
* 候補
* 投票方式
  * 候補を１つ選択
  * 候補を複数選択
  * 候補にランクをつけて複数選択
  * 集計方式
    * 投票者の属性による重み付け
    * ランクによる重み付け
  * 候補選択方式
    * 一つのみ
    * 比例配分
    * ランク付け
* 参加者
  * 投票実行者
  * 棄権者


## 扱うもの
* 投票期間
* 投票時間
* 投票券
* 多数決アルゴリズムのプラグイン


## 扱わないもの
* 投票の権利を持つかどうかのチェック
* 投票対象地域

# 入出力

## init command
### 入力
* period
* hours
* method
* candidates

### 出力
success or error

### 状態
listen

## terminate command
### 入力
* SIGNAL
* reason 

## 出力
* success or error
* 途中結果

## vote command 
### 入力
TODO: 
### 出力

# 選挙のと連携
選挙と投票は概念が異なる

