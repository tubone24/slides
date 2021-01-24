# MQTTと電子ペーパーを使って年賀状を作る

Yu Otsubo

---

## 自己紹介

- Yu Otsubo
- 27歳・独身
- 普段はChatbotの開発をしてます

<img src="img/me.jpg" alt="自分" align="right" width="300" height="300">

---

## 日本人ならではの悩み

---

<img src="img/2021-01-24_19h00_43.png" alt="Yahoo知恵袋" align="center">

---

## 悲しいですねっ....

<!-- .slide: data-background="#02A8F4" -->

---

## 送らなければいいのでは？(正論)

---

<img src="img/arashi1.jpg" alt="嵐" align="center" >

---

<img src="img/arashi2.jpg" alt="嵐年賀状送れ" align="center" >

---

# ということで

---

# なんとかしてみよう

---

## 年賀状の何がめんどくさいのか？

- - -
- 年賀はがきをたくさん購入しなければいけない <!-- .element: class="fragment" data-fragment-index="1" -->
- 同じ文章をたくさん書かなければいけない <!-- .element: class="fragment" data-fragment-index="2" -->
- 気の利いたイラストを載せなければいけない <!-- .element: class="fragment" data-fragment-index="3" -->
- 提出期限がある(1/1必着の場合) <!-- .element: class="fragment" data-fragment-index="4" -->

---

## 全部解決してみよう！ IoTで。

<!-- .slide: data-background="#ff5152" -->

---

### 注意

私はIoTの専門家ではないので、いい加減なことを言っているかもしれません。

ご了承ください。

---

## 雑なアイディア

<img src="img/gainen.png" alt="概念" align="center" >

---

# 材料準備

技術選定も兼ねて材料集めに入ります。

---

## 電子ペーパー

<img src="img/2021-01-24_19h56_19.png" alt="電子ペーパー" align="center" >

結構中華製電子ペーパーがAmazonに売ってます。

本当は[M5Paper](https://m5stack.com/products/m5paper-esp32-development-kit-960x540-4-7-eink-display-235-ppi?variant=37595977908396)使いたかった...

これで本物に近い年賀状デバイスができそうだ！

---

## Raspberry PI

<img src="img/NtXAaISl.jpg" alt="RaspberryPi" align="center" >

家に転がっていたラズパイに電子ペーパーをドッキング！！

もともとドッキングしてたCoral君とはバイバイ

---

## Web Application

<img src="img/modernArch.png" alt="Modern Arch" align="center" >

最近流行っている組み合わせをお勉強で使ってみる

---

## MQTT

<img src="img/mqtt.png" alt="Modern Arch" align="center" height="600" >

IoT機器を絡めたPub/SubモデルはMQTTが有名なので使ってみる

---

#### 雑に設計

<img src="img/arch.png" alt="Modern Arch" align="center" >

- フロントにはModern Brothersを利用
- バックエンドにはAPIサーバーとしてFastAPI、MQTT利用のためにPahoを利用
- MQTTブローカーは自前でDocker上にMosquittoで構築
- Pahoを使って電子ペーパー搭載のラズパイに年賀状を送る

---

## 今年が終わっちゃう！💦

早く作らないと...。

<img src="img/2021-01-24_23h47_09.png" alt="calender" align="center" >

<!-- .slide: data-background="#B867C6" -->

---

## できた！

デモ動画

---

---

# Thank you

---
