---
title: "Hugo + Github Pagesで個人サイトを作る"
date: 2022-07-27T18:37:07+09:00
tags: ["Tech",]
archives: ["2022/07"]
draft: false
---


1. Github上でリポジトリを作る


2. ローカルにクローンして、[クイックスタート](https://gohugo.io/getting-started/quick-start/)をやる(テーマは自分の好みでAnankeからBlondeに変更)


3. [Hugo: Host on Github](https://gohugo.io/hosting-and-deployment/hosting-on-github/)に従ってサイトを公開


このとき、Github上で設定を忘れるとサイトが正しく公開されないので注意
- https://gohugo.io/hosting-and-deployment/hosting-on-github/#github-pages-setting
  (Github Pagesで公開されるのはmainブランチ)
- https://gohugo.io/hosting-and-deployment/hosting-on-github/#change-baseurl-in-configtoml


最後の独自ドメイン設定をしなくてもよければ、この時点で`<USERNAME>.github.io`か`<ORGANIZATION>.github.io`でHugoサイトが公開されているはず


4. 独自ドメインを設定する


下記に従って設定する
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
- 今回はお名前.comで使ったドメインをCNAMEレコードを設定
  - https://www.onamae.com/guide/p/70


5. Google Analytics設定


6. Disqus設定
