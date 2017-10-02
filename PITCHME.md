# るりまサンプルコード追加プロジェクト
通称 Ruby Polisher Project

+++

勝手にプロジェクト名を決めました

+++

ツイートするときに `#ruby_polisher`
のハッシュタグを使っています

---

## Ruby Polisher Project とは
Ruby の公式リファレンスである  
「るりま」のサンプルコードを拡充するプロジェクト

+++

「るりま」はここ
https://docs.ruby-lang.org/ja/

---

## なぜサンプルコード拡充をするの？

公式リファレンスの充実は言語を利用する人が快適な言語ライフを送る意味で  
ボディーブローのように効果があるのではないか？

+++

新たにRubyを学習する人

+++

そんな人が調べごとをするとき

+++

迷わず学習できる状態にすることの価値

+++

プライスレス

---

## きっかけは？

きっかけは数学ガールの著者として有名な  
結城 浩 先生の一言でした。

+++

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">Rubyのドキュメントは、<br><br>「そのままコピペして動く典型的なコードを最初に見せてほしい」<br><br>という点だけが要望。requireが抜けてたり、そもそも典型的コード例がなかったり、そういうのやめて…<br><br>OSSなんだから、自分でcontribしろよという意見もあるとは思いますが…</p>&mdash; 結城浩 (@hyuki) <a href="https://twitter.com/hyuki/status/885435631802777601?ref_src=twsrc%5Etfw">2017年7月13日</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

+++

や　り　ま　し　ょ　う

+++

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">Rubyユーザーのてぃーびーと申します。もしよろしければ結城先生の要望に関して修正箇所のリストアップ・修正の実作業や協力者の声がけなどひとまとめでやろうと思っています。まずは方針をまとめた上でご提案させていただこうと思っています。提案はどなたにお伺いをたてればよろしいでしょうか？</p>&mdash; てぃーびー 📺 (@tbpgr) <a href="https://twitter.com/tbpgr/status/885615106314326016?ref_src=twsrc%5Etfw">2017年7月13日</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

---

## どのくらい足りないの？
プロジェクト開始時点で約 8,000 件足りませんでした

+++

```sh
$ ruby -e 'methods = Dir["method/**/*.html"]; methods_with_example = methods.select{|m| File.read(m).include?("<pre>") }; puts "#{methods_with_example.count}/#{methods.count}"'
2628/11039
```

+++

11,039 - 2,628 = 8,411 件の不足

+++

マンパワーが必要！

---

## 強力な味方

[hanachin](https://github.com/hanachin) 氏の無双

+++

サンプル未作成メソッドの検出を自動化

+++

require が不足しているサンプルを大量に修正

+++

るりま執筆支援スクリプトを作成

+++

便利スクリプトはこちら

* https://github.com/hanachin/rurema-scripts
* https://github.com/hanachin/rurema-kaku

---

## 2017 RubyKaigi とともに広まる
[【緩募】Rubyリファレンス・マニュアル＝るりまで不足中のサンプルコード8,000件を一緒に作りませんか？ - Tbpgr Blog](http://tbpgr.hatenablog.com/entry/2017/09/17/232557)

+++

RubyKaigi 実施の時期に記事を公開。

+++

ブックマーク200オーバーを記録。  
取り組みが一気に広まる。

---

## rurema esa 爆誕
🐣

+++
✨🐥✨

+++

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">作業するための割り振りとか話すesaとか作る？</p>&mdash; 🌈 (@ppworks) <a href="https://twitter.com/ppworks/status/909431453871509511?ref_src=twsrc%5Etfw">2017年9月17日</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

+++

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">てぃーびーさん、ほんじゃesa作ってもらえれますか？よしなにアレします&quot;(\( ⁰⊖⁰)/)&quot;</p>&mdash; 🌈 (@ppworks) <a href="https://twitter.com/ppworks/status/909434452530536448?ref_src=twsrc%5Etfw">2017年9月17日</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

+++

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">ありがとうございます！<br>新規作成しました。今回の件だけではなく利用できるようにidは &quot;rurema&quot; にしてあります。<a href="https://t.co/DJXkw0e5Ia">https://t.co/DJXkw0e5Ia</a></p>&mdash; てぃーびー 📺 (@tbpgr) <a href="https://twitter.com/tbpgr/status/909436976771735552?ref_src=twsrc%5Etfw">2017年9月17日</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

+++

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">rurema esa が爆誕した</p>&mdash; てぃーびー 📺 (@tbpgr) <a href="https://twitter.com/tbpgr/status/909439178772946945?ref_src=twsrc%5Etfw">2017年9月17日</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

+++

esa社の皆様に感謝 (\\( ⁰⊖⁰)/)

+++

サンプルコード追加に興味がある方々を  
[rurema esa](https://rurema.esa.io/) でお待ちしてます


+++

招待コードは doctree/rurema の Issue 433 をご確認ください

https://github.com/rurema/doctree/issues/433

## 取り組みは広がっている

サンプルコード追加の月次レポート

http://tbpgr.hatenablog.com/entry/2017/10/02/010000

+++

rurema esa の参加者

2017/10/01 時点で 50 名

---

## Ruby 磨きませんか？

## Fin
