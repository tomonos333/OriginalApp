# OriginalApp
## 概要・企画
簡易SNSアプリ
「行きたい、見たい、食べたい」希望のリストをシェアできるアプリ
※もう少し簡潔なキャッチフレーズが欲しい。。

## 背景
#### ・こんなシーンはないか(課題)
食べログアプリのように、
特定ユーザをフォローすると、ユーザの食べたい・食べたの記録を知ることはできる。
しかし、特定のユーザとの食べたい・食べたを共有管理するには機能が満足ではない。

「今日何食べる？」
→「んー。。なんでもいい。歩いて決めるか。。」
→「前に行きたいとこあるって言ってたよね？どこだっけ？」

「今日のお店どうだった？」
→「よかった！こんどここに来る機会があればまた寄ってみよう」（忘れられる)
→「あそこのお店もおいしそうだったから今度行ってみたいな」(忘れられる)


お互いの希望が事前に整理共有されていないため、
・お互いの希望に対する合意形成までの時間がかかる。
・希望が達成されるまでのストーリー、その繋がりはなく記憶に残りずらい

#### もしこんなものがあったら(解決)
よく食事にいく人、遊びにいく人と、
ここに来たら○○を食べてみたい、今度夜時間があったら○○に行こうなど、
お互いの希望をリスト化・共有することができていたら、お互いの合意形成が
スムーズになるだけでなく、それらが達成されるまで、また達成された後まで
その希望に対してのストーリーを共有して楽しむことができる。


## 機能（できる、したい）

・「行きたい、見たい、食べたい」希望を登録リスト管理できる
・管理しているリストを特定のユーザをシェアできる
(・リストに対してコメントできる)
・管理しているリストはカテゴリ（映画、料理、エリアetc)分けして管理することができる
・住所情報を登録すると、リストをマップ上でプロットできる


## 画面イメージ・画面ごとの機能

※画面ごとの機能を箇条書き.画面はおいおい具体化していきます


イメージとして,タブバーによってそれぞれ表示される画面がかわるイメージ
1. ホーム：誰との共有リストを表示するか選択できる
2. 行きたい：リストを管理・編集するページ
3. ＋：リストを登録するページ
4. 行った：行きたいリストにて達成したものをこちらで管理
5. 設定：諸設定画面。シェアしたいユーザの登録？連携？などはここで

![home.png](C:\Users\t2140028\Google ドライブ\ios\home.png)

### 1・ホーム
・シェアしているどのユーザについてのリスト管理をするか選択によって切り替えられる
・ユーザのセルを選択すると行った・行きたいリストに関する統計情報・グラフなどを表示できればいいかなと思う

### 2・行きたい
2,4については、現状タスク管理アプリのようなイメージになります。
・画面上に「リスト」「マップ」の2つのタブがあり、どちらかの表示形式をとれる
・「リストではフォルダなどユーザが任意で階層構造を作って管理できるようにする
　「例：グルメ、映画、デート」
### 3・＋
リストを新規作成する画面
・カテゴリ、お店の名前、住所情報、URL、タグ？、メモ

### 4・行った
・2もしくは3にて「行った」フラグを建てられたリストを管理
・画面構成は基本的に2と同じ
・ユーザによる評価などの要素も追加(ランキング？)できるとおもしろいかも
### 5・設定
・シェアするユーザを設定
・このアプリについて
