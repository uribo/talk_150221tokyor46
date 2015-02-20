# Japan.R補完計画

2015年２月21日 ニフティ株式会社 新宿フロントタワーにて開催されるTokyo.R#46での発表資料（LT）

## 概要

2010年にはじまり、今年２月、46回目の開催を迎えたTokyo.Rの歴史を振り返り、これまでのまとめとこれからについて議論しようとしたのだけど、いざ解析をはじめた途端、少し前の発表で同様のことが行われており、調べてみると定期的にこのような発表が行われていることがわかった。Tokyo.Rでは、長い歴史の中でたくさんの情報が蓄積されているが、その情報は一括にまとめられていない。発表者は今回のような事案もこうした問題から発生していると**決めつけた**。また、これまでと同じことをしてもつまらないので、なにか別なことをしようと思い、自分のような新参者、世間知らずが「ネタ被り」を防ぐためのRパッケージを作ることにした。対象としたのはTokyo.Rのみならず、日本全国各地に存在するRコミュニティとし、より包括的にRコミュニティの情報をまとめることを目指した。[Japan.useRパッケージ](https://github.com/uribo/Japan.useR)は各地のRコミュニティの活動内容を補完することを目標としており、開発がはじまった段階である。Japan.useRに含まれるデータとTokyo.Rを比較することで、なにか見えてくるものがあるかもしれない。

## 色見本

ref) https://dribbble.com/shots/1899538-Luna

```r
library("rvest")
library("designer")
get_pal(url = "https://dribbble.com/shots/1899538-Luna", show = FALSE)
[1] "#36353B" "#FDD586" "#5FB8FC" "#29F6E7" "#F7417A"
[6] "#FEE08C" "#17CCB7" "#648992"
```

## リンク

* [atnd](https://atnd.org/events/61553)
* [勉強会発表内容一覧 Tokyo.R](http://lab.sakaue.info/wiki.cgi/JapanR2010?page=%CA%D9%B6%AF%B2%F1%C8%AF%C9%BD%C6%E2%CD%C6%B0%EC%CD%F7#p15)... 第１回から第35回（20131109）まで
* http://www.rpubs.com/dichika/rank2014
* http://www.slideshare.net/dichika/tokyor17-9449827
* http://www.trifields.jp/r-slideshare-list-887
* http://rpubs.com/yamano357/40263
* http://www.slideshare.net/dichika/tokyor17-9449827
* http://estrellita.hatenablog.com