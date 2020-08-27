# ラーメンたべたい

Yu Otsubo

---

## 自己紹介

- Yu Otsubo
- 27歳・独身
- Chatbotの開発をしてます

<img src="img/me.jpg" alt="自分" align="right" width="300" height="300">

---

## 突然ですが

---

<!-- .slide: data-background="img/img_bb7d5b7877588c054e79d31c1b4e6587231905.jpg" -->

---

## いかがお過ごしでしたか？
<!-- .slide: data-background="#02A8F4" -->

---

## GoToできないキャンペーンをどう有意義に過ごすか？
- - -
- ゲームする <!-- .element: class="fragment" data-fragment-index="1" -->
- 本を読む <!-- .element: class="fragment" data-fragment-index="2" -->
- YouTubeを見る <!-- .element: class="fragment" data-fragment-index="3" -->
- サービス開発をする <!-- .element: class="fragment" data-fragment-index="4" -->

---

## サービス開発をする
<!-- .slide: data-background="#ff5152" -->

---

## じゃあ何作る？

---

<div class="r-stack">
  <img class="fragment" src="img/2020-08-24_17h53_00.png">
  <img class="fragment" src="img/2020-08-24_17h55_17.png">
  <img class="fragment" src="img/2020-08-24_22h09_39.png">
</div>

---

## みんなラーメンたべたいらしい

![img](img/food_ramen_iekei.png)

---

## 4連休でラーメンに関係するサービスを開発しよう
<!-- .slide: data-background="#01BBD4" -->

![img](img/2020-08-2420.34.30.png)

---

# 1日目

---

![img](img/chuunen_neet_snep.png)

だらだら...

---

# 2日目

---

![img](img/chuunen_neet_snep.png)

だらだら...

---

# あと2日しかない！！
<!-- .slide: data-background="#B867C6" -->

---

## RTA始動！

---

## ラーメン食べたい開発RTA始動！

> 世の中はすべてRTAである
> <footer>—Yu Otsubo</footer>

---

## ラーメン食べたい開発RTAの掟

- 残り<font color="#ff4500">**2日**</font>でラーメンに関するそこそこのサービスを作る <!-- .element: class="fragment" data-fragment-index="1" -->
- カネがないので<font color="#ff4500">**無料**</font>で作る <!-- .element: class="fragment" data-fragment-index="2" -->
- <font color="#ff4500">**要望**</font>には全力で答える <!-- .element: class="fragment" data-fragment-index="3" -->
- ちゃんと<font color="#ff4500">**テスト・CI**</font>にも力を入れる <!-- .element: class="fragment" data-fragment-index="4" -->

---

# RTA1日目
<!-- .slide: data-background="#01BBD4" -->

---

## とりあえず設計

---

## 10分で書いた

![img](img/wire.png)

---

## 技術選定

開発RTAでは難しすぎず、かと言って陳腐すぎない技術を選ぶことが勝利の鍵

---

## LINE Messaging API

LINEにBotアカウントをつくる

無料だしドキュメントが本当に丁寧で開発RTA民にとってはありがたいおもちゃ

<video src="https://developers.line.biz/media/videos/messagingapi.mp4"></video>

---

## Google Apps Script

Googleスプレッドシートのマクロ機能だが、APIコール、エンドポイント作成など大体のことはできます。

こちらも無料だし、RTA民にはありがたいおもちゃ

![img](img/gas.png)

---

## Clasp

GASでの開発をサポートしてくれるすごいやつ

- TypeScriptで書ける！
- テストも書ける！
- CIに乗っけやすい！

![img](https://user-images.githubusercontent.com/744973/42856573-a5d96d7c-89fa-11e8-9d69-8d2c66f00d8d.gif)

---

## ぐるなびAPI

位置情報を送ると、近くのお店情報を返してくれる

![img](img/gurunavi-logo.png)

---

## 雑シーケンス

つくるぞ〜

![img](img/gas-line.png)

---

## できた

<video src="https://github.com/tubone24/slides/raw/master/20200824-ramen-tabetai/img/dekita.mp4" width="312" height="624"></video>

---

## 1日目終了

---

## 2日目
<!-- .slide: data-background="#FF3F80" -->

---

## 要望が来る

![img](img/2020-08-24_17h59_34.png)

ラーメンライフログを作って！

---

## RTAの掟

要望には全力で答える

---

## 技術選定

---

## Firebase&Nuxt.js

![img](img/nuxt_gas.png)

Firebaseでホスティング&DB。ライフログ画面はNuxt.jsでパパっと作る

---

## できた

<video src="https://github.com/tubone24/slides/raw/master/20200824-ramen-tabetai/img/ramen.mp4" width="312" height="624"></video>&nbsp;<video src="https://github.com/tubone24/slides/raw/master/20200824-ramen-tabetai/img/ramen2.mp4" width="312" height="624"></video>

---

## RTAの掟

テスト・CIもきちんと

---

### テスト書いた/CI整えた！

<div class="r-stack">
  <img class="fragment" src="img/badge.png" width="599" height="381">
  <img class="fragment" src="img/test_actions.png" width="831" height="460">
  <img class="fragment" src="img/actions.png" width="636" height="350">
</div>

GitHub ActionsとJestを使って継続的な開発も余裕！

---

## RTA成功🎉

ニューノーマルな休日の過ごし方でした。

みんなもやってみよう！

PRも待ってます。 <https://github.com/tubone24/ramen-tabetai>

---

### ラーメンたべたいBotをフォローしよう!

![img](img/qr.png)&nbsp;[![img](img/68747470733a2f2f7363646e2e6c696e652d617070732e636f6d2f6e2f6c696e655f6164645f667269656e64732f62746e2f6a612e706e67.png)](https://lin.ee/Y9mUrIN)

---

# Thank you

---