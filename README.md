# ゲーム紹介

## タイトル
### One hour dungeon

## ジャンル
### ローグライクRPG （スタートや階層が変わるごとに自動的にMAPやアイテム等の配置が変わるゲーム）

## 操作方法
### スペースキー    ゲーム開始
### 十字キー       キャラクターの移動
### Aボタン        攻撃
### Pボタン        回復アイテム（ポーション）
### Bボタン        攻撃アイテム（Blazegem)
### Rボタン        戦闘から逃げる（確率で失敗することも）
### Sボタン        ゲームスピードの変更

## 操作方法（オリジナル要素）
### Qボタン        キャラクター情報のセーブ機能
### Zボタン        セーブした情報から再開できる機能

## ゲームコンセプト
### タイトル通り、１時間程度で遊べるゲームを市販の参考書を見ながら模写をしつつ、基本コードに自身が考えた要素を付け加えたゲームになります
### 出てくるモンスターは全部で１１種類。下の階層に行くごとに出てくるモンスターの種類が増え強くなっていきます
### キャラクターが移動する毎にFOOD置が０．５ずつ減少していきます。FOOD値があるうちは歩く毎にLIFE値が１ずつ回復しますが、FOOD値が０になると逆にLIFE置は５ずつ減少することになります
### ダンジョン内に配置されている宝箱には、回復アイテムであるPOTIONと攻撃アイテムであるBLAZEGEMが、現在のFOOD値を半分にしてしまうトラップアイテムが手に入ります
### 繭は、敵との戦闘になったり、FOOD値を回復するアイテムが確率で発生するようになっています

## オリジナル要素
### 武器に耐久値を設けています。モンスターに攻撃するたびに耐久値が５ずつ減っていきます。ダンジョン内に落ちている剣アイテムを拾うと耐久値が１０回復するようになります。耐久値の上限は１００に設定しています。
### 宝箱を開けるとアイテムが出てきますが、稀にモンスターが出てくるように変更しています。通常のモンスターよりも手強くしています。
### RPG要素に欠かせないセーブ、ロード機能も実装しています。セーブ機能はいくつもデータが保存されるのではなく新しいデータを上書きされるようにしています。
### また、一度ロードをするとセーブデータが削除されるので同じセーブデータは使用できなくしています。