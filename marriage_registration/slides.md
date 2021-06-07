---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://i.imgur.com/8ysSgtb.jpg
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
---

# 継続的なデリバリーができる婚姻届を作ろう

Make a marriage registration for continuous delivery!

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<a href="https://github.com/tubone24" target="_blank" alt="GitHub"
  class="abs-br m-6 text-xl icon-btn opacity-50 !border-none !hover:text-white">
  <carbon-logo-github />
</a>

---

# 自己紹介

## Yu Otsubo
- 普段は業務でチャットボット作ってます
- 趣味でネットの**産業廃棄物**をたくさん作ってます
- Tech-inでふざける人

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 継続的デリバリーとは？

そもそも継続的デリバリーって何でしょうか？

**継続的デリバリー**とは、ソフトウェア開発手法の 1 つで、コード変更が発生すると、自動的に実稼働環境へのリリース準備が実行されるというものです。

つまり、**繰り返しやるような**めんどくさいリリース準備を自動化する、ということです。

![img](https://i.imgur.com/JzpQU5W.png)

引用: https://aws.amazon.com/jp/devops/continuous-delivery/

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# PullRequestを主軸にした開発スタイル

PRとも呼ばれるPullRequestとはいったいどんなメリットがあるのでしょうか？

何かあなたがもっとこうしたほうがいいと感じたプロダクトがあるならPullRequestを出して、プロダクト改善を図ることができます。

PullRequestではレビュアーが承認(Approve)したものが本流に取り込まれるのです。

![img](https://i.imgur.com/LaTqmtO.png)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 一方で

<style>
h1 {
  background-color: #2B90B6;
 height: 400px;
 display: flex;
 justify-content: center;
 align-items: center;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 未婚率の推移

近年増えている未婚。日本の未来は明るいとは言えない。

![img](https://i.imgur.com/L5SJCon.png)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 結婚できない理由

男女とも適当な相手にめぐり会わないらしい。

![img](https://i.imgur.com/VWZS1Fh.png)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 恋愛できない男女

出会いの場や、声のかけ方に不安を感じているらしい。

![img](https://i.imgur.com/WzbcSS1.png)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# まとめると

<style>
h1 {
  background-color: #2B90B6;
 height: 400px;
 display: flex;
 justify-content: center;
 align-items: center;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 気軽にPRを送りあって婚活し、CICDで手軽に結婚しちゃおう

<style>
h1 {
  background-color: #2B90B6;
 height: 400px;
 display: flex;
 justify-content: center;
 align-items: center;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# ざっくりアイディア

GitHubのPRを使って気になる相手とマッチング。CICDが回って婚姻届ができる！！

![img](https://i.imgur.com/VogpT7W.png)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 注意事項

婚姻届は[戸籍法施行規則第59条に指定されている様式](http://www.moj.go.jp/content/000116683.pdf)に従っていれば受理されるらしい。

- A3の長方形の用紙に印刷し、切り込みを入れたり形を変えたりしてはいけない
- 規定の項目が揃っている必要がある(婚姻の届書(戸籍法施行規則附録第12号)に則っていなければならない)

![](https://i.imgur.com/ZoY0EYlt.jpg)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# できた！！

- 印字は**ReportLab**を使用
- CICDは**GitHub Actions**を使用

![img](https://i.imgur.com/1l7MIIi.png)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-right
image: https://i.imgur.com/VEiAVch.png
---

# Code

結婚したい相手のコンフィグにたいしてこんな感じでYamlを書きます。

```yaml
wife:
  last_name: 貫井
  last_name_pos: [420,590]
  last_name_kana: ぬくい
  last_name_kana_pos: [421,623]
  first_name: はゆ
  first_name_pos: [502,590]
  first_name_kana: はゆ
  first_name_kana_pos: [502,623]
  birth_year: 平成7
  birth_month: 6
  birth_day: 6
  address_first: 東京都小金井市貫井北町
  address_first_pos: [422, 545]
  address_second: ３丁目　４
  is_banchi_address: false
  address_go: １０
```

---

# ランディングページも作ってみました

Forkしてあなたも今日からPR婚活CICD結婚をしましょう！

[Learn More](https://marriage-registration-landing-page.vercel.app/)

![img](https://i.imgur.com/g7UsnDS.png)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 結論

日本の未来は明るくなったと思ったがよく考えたら...

- そもそも、GitHubだけ見て結婚したい人はいない
- CICDで継続的に婚姻届をデリバリーしてはいけない

## 真面目に婚活します！！

花嫁募集中！ 

<https://github.com/tubone24/marriage_registration>

---
