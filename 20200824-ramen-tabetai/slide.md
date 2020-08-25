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

## StayHomeをどう有意義に過ごすか？
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

![img](img/baseball_pitcher_woman.png)

某野球美少女アニメを一気観する...

---

# あと2日しかない！！
<!-- .slide: data-background="#B867C6" -->

---

## ラーメン食べたいBot開発RTA始動！

> 世の中はすべてRTAである
> <footer>—Yu Otsubo</footer>

---

## ラーメン食べたいBot開発RTAとは？

- 残り*2日*でラーメンに関するそこそこのサービスを作る <!-- .element: class="fragment" data-fragment-index="1" -->
- カネがないので*無料*で作る <!-- .element: class="fragment" data-fragment-index="2" -->
- エラーを吐いても*弱音*を吐かない <!-- .element: class="fragment" data-fragment-index="3" -->
- ちゃんと*テスト*書いて、*CI*にも力を入れる <!-- .element: class="fragment" data-fragment-index="4" -->

---

## とりあえず設計

おばあちゃんが言っていた…

設計をちゃんとしなさいと

---

## 10分で書いた

![img](img/wire.png)

---

## 技術選定

開発RTAでは難しすぎず、かと言って陳腐すぎない技術を選ぶことが勝利の鍵

---

## Messaging Platform
<!-- .slide: data-background="#FF3F80" -->

---

## LINE Messaging API

LINEにBotアカウントをつくる形にする

無料だしドキュメントが本当に丁寧で開発RTA民にとってはありがたいおもちゃ

---

## Bot本体(サーバサイド)

---

## Google Apps Script

Googleスプレッドシートのマクロ機能だが、APIコール、エンドポイント作成など大体のことはできます。

こちらも無料だし、RTA民にはありがたいおもちゃ

---

## でもちょっとGASってテストもCIも大変なんだよね

---


# デフォルトカラー

>>>
<!-- .slide: data-background="#ff5152" -->
aaa
# FF5152

>>>
<!-- .slide: data-background="#02A8F4" -->
aaa
# 02A8F4

>>>
<!-- .slide: data-background="#B867C6" -->
aaa
# B867C6

>>>
<!-- .slide: data-background="#FF9000" -->
aaa
# FF9000

>>>
<!-- .slide: data-background="#01BBD4" -->
aaa
# 01BBD4

>>>
<!-- .slide: data-background="#FF3F80" -->
aaa
# FF3F80

---

## Markdownで書くから管理も簡単



**次は２ページ目**

<aside class="notes">
  発表者が見るノート   
  伝えたいことをメモ  
</aside>


---
### ページ２
- - -
1. 数字付きのリスト
1. 番号はどうでもいい

>>>

### ページ２−１
ページ２から垂直に下に遷移する  
垂直遷移には補助的な説明を

- 普通のリスト
- 簡潔にね

>>>

### ページ２−２
コードもばっちり

```js
let a = 1;
let b = 2;
let c = x => 1 + 2 + x;
c(3);
```

---

## 写真
写真
![img](https://i.imgur.com/APah4wG.jpg)

---
## 絵文字

 🦔 

---
## Video
video
<video src="https://github.com/tubone24/blog/raw/master/static/assets/chainer-test.mp4"></video>
