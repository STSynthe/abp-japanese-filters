# なにここ

私（STSynthe a.k.a. えむ）個人が手入れしている日本国内Adblock Plus用フィルタです。

元のABP Japanese filtersは問題があり[^badboy]、個人的に気になる部分の排除・最適化しました。今まで自分用として使っていましたが、現在（2022年5月中旬）はこれを共有して使うのは自由です。

**私への連絡は「[issues](https://github.com/STSynthe/abp-japanese-filters/issues)」にて**。<span lang="en">**Contact me at "[issues](https://github.com/STSynthe/abp-japanese-filters/issues)"**.</span>

# 方針

* 短いフィルタになるべく頼らない
* 広告主がお金を払って掲載しているコンテンツをいろんな言い方があるがとりあえず「広告」と呼び、それを基本ブロックの対象とする
* 慎ましいテキスト広告をできる限り排除しない
* 慎ましい自社広告をできる限り排除しない
* エンターテイメント的な広告をできる限り排除しない（例：ニコニ広告、見返りのないバナーリンク、人道的もしくは[人権道徳的](https://www.youtube.com/watch?v=GjVCYhpkJiA)な広告など）
* 解析系、トラッキング系のコードをブロックする
* 広告が抜けた事による過剰で無駄なスペースが広がっているエレメントの非表示（ただし積極的な取り組みをしない）
* 突発的に発生する有害（フィッシング、スパイウェアなど）なサイトは排除しない[^harmful]

# 購読

ABP Japanese filtersとは別に

* [ABP filters](https://github.com/abp-filters/abp-filters-anti-cv) 
* [EasyList](https://easylist.to) 

以上のフィルタを合わせて購読することを推奨しています。ただし組み合わせ過ぎはおすすめしません。***重たくなる原因***です[^performance]。

≫ [Subscribe - フィルタの購読（インストール）](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2FSTSynthe%2Fabp-japanese-filters%2Fmaster%2Fabpjf.txt&amp;title=ABP%20Japanese%20filters) ≪ - （[ソース](https://raw.githubusercontent.com/STSynthe/abp-japanese-filters/master/abpjf.txt)）

# 問題報告

ご協力感謝します。

このフィルタが引き起こしてる表示の乱れや動作不良の対応は[issues（問題報告）](https://github.com/STSynthe/abp-japanese-filters/issues/new/choose)のみ受け付いてます[^motivation]。

- ***問題を引き起こしてるウェブサイトURL***（ウェブサイトのタイトルのみ記入不可）
- 表示の乱れや動作不良（あからさまなら記入不要）
- 本来の表示や動作（あからさまなら記入不要）
- ***環境***（OS、ブラウザ、拡張機能、購読してるフィルタなど）

を添えて投稿して下さい（***太字***は必須項目）。

# 免責

* このフィルタを利用したことによる何らかの障害を受けた。
* 動作保証。
* issuesや github.com 以外での対応[^motivation]。
* コミット減速あるいは停止[^yaruki]。

# 言い訳

## uBlock Origin / AdGuardに対応してますか？

使えますが完動しません。<br>私が「スニペットフィルタ」と呼ばれるフィルタパターンを採用してから***非対応***になりました。

ここではフィルタ文の書き方について詳しく説明しませんが、Adblock Plusの基本フィルタで書いていれば他の広告ブロックツールもほぼ対応しています。ただ「スニペットフィルタ」と呼ばれる文法に違いがあるために非対応に成るということです。

現時点（2022年5月中旬）で他の広告ブロックツールに対応する考えはありません。コンバーターツールみたいなのを使えば解決すると思いますが、今はその時期ではないと考えています。敬遠ではなく、他とも仲良くやってく方向です。

## 本家にPullリクエストした方が今使ってる方々へ貢献できるのでは？

更新が絶え、なおかつ方針の違いによりしません。

* [github.com/k2jp/abp-japanese-filters/wiki/FAQ](https://github.com/k2jp/abp-japanese-filters/wiki/FAQ)
* [github.com/k2jp/abp-japanese-filters/wiki/Support_Policy](https://github.com/k2jp/abp-japanese-filters/wiki/Support_Policy)

## プライバシーポリシー云々の表示を消してほしい

ダメです。

プライバシーポリシーとは「[個人情報の保護に関する法律](https://elaws.e-gov.go.jp/document?lawid=415AC0000000057)」に基づき、個人情報を収集している旨を閲覧者に必死でアピールしなければならないことを理解するべきです。

「法令」による義務、「広告」ではないため、どのみちこの件は無視しています。

## アマゾン アソシエイト（アフィリエイト）のリンクが消されている

単純な「広告」ではありますが、それ以上にアマゾンの規約に反するなど、それら多く見かけるようになりました[^amazon]。それらを総合的に判断し非表示を決定しました。

表示が望みであれば、ホワイトリストにドメインを入れるだけで簡単復活です。

## YouTubeとか正しく見られるようになりましたか？

成りました。[#購読](#購読)にある推奨フィルタと合わせて使うのがベストです。

またYouTubeに限らず「広告」と関係ないモノを弾いてるフィルタは撤去していく考えです。

### 視聴履歴とかアノテーションとかは切ったままの方が良かった…

YouTubeの視聴履歴はプライバシー侵害にあたると疑問を抱くかと思ったり思わなかったりしますが、望みであればGoogle側の設定で履歴保持しない設定を自身でできるようになってます。そのようなモノをフィルタで弾くことはありません。

## 簿記

オチが良かったので、共有させてください。

* [twitter.com/ssig33/status/1094614899022426112](https://twitter.com/ssig33/status/1094614899022426112)

# Links

## my

* [Git](https://github.com/STSynthe/abp-japanese-filters)
* [コミットログ](https://github.com/STSynthe/abp-japanese-filters/commits/master)
* [stsynthe.github.io](https://stsynthe.github.io/abp-japanese-filters/)

## tools

* [Adblock Plus](https://adblockplus.org/) - 今の本家、重厚。
* [uBlock Origin](https://ublockorigin.com/jp) - ADPより身軽さをアピール。
* [Vivaldi ブラウザ](https://vivaldi.com/ja/) - フィルタ内蔵の素晴らしいブラウザ。

## filters

| フィルタ | ライセンス | 備考 |
| :-- | :-- | :-- |
| [ABP filters](https://github.com/abp-filters/abp-filters-anti-cv)  | GNU GPL v3.0 | ベースとして入れておきたい一品。 |
| [EasyList](https://easylist.to)  | GNU GPL v3.0 + CC BY-SA 3.0 | より強力・スマート。必須フィルタといっても良いぐらい。 |
| [豆腐フィルタ](https://github.com/tofukko/filter) | コピーレフト？ | ソースが綺麗に整理されてる。2022年時点更新継続中。 |
| [もちフィルタ](https://eeii0a5l.github.io/mochifilter_homepage/mochi.html) | パブリックドメイン[^mochi] | 最低限のコモンで弾いてるためか、より軽量を唱っている。2022年時点更新継続中。 |
| [Yuki's uBlock Japanese filters （雪フィルタ）](https://github.com/Yuki2718/adblock) | CC BY-SA 4.0 | uBlock Origin向けのフィルタ。2022年時点更新継続中。 |
| [ABP Japanese filters（本家）github.com/k2jp/abp-japanese-filters](https://github.com/k2jp/abp-japanese-filters) | GNU GPL v3.0 + CC BY-NC-SA 4.0 | このフィルタをベースに開発してます。2021年頃に更新が途絶える。 |

## memo

* [フィルタ構文 - Adblock Plus](https://help.eyeo.com/adblockplus/how-to-write-filters)
* [スニペットフィルタ構文 - Adblock Plus](https://help.eyeo.com/adblockplus/snippet-filters-tutorial)
* [ABP Test Pages - Adblock Plus](https://testpages.adblockplus.org/)

[^badboy]: 1万行を超えてるためにパフォーマンス低下と誤爆、さらにuBlock Originからは[「ABP Japanese filtersは酷い」と酷評され](https://www.reddit.com/r/uBlockOrigin/comments/apby98/default_included_abp_japanese_filters_just_sucks/)、デフォルトのリストから外されている。
[^motivation]: （2022年5月中旬時点）READMEにあるように元は自分用でした。以後もissues以外での不具合対応するモチベーションはないです。ドネーションも今のところ考えてません。
[^mochi]: （2022年5月上旬時点）「**もちフィルタは、EasyListと豆腐フィルタから必要最小限のフィルタを抜き出したもの**」としてる。真偽は兎も角、[EasyListはライセンスを明確](https://easylist.to/pages/licence.html)にしている…
[^performance]: ジェネリックや正規表現、拡張機能の多用はパフォーマンス低下に繋がることが確実です。またEasyListだけで6万行超えています。
[^yaruki]: 「やる気低下」というコミットが次第に露呈するはずです。
[^amazon]: [Amazonアソシエイト・プログラム運営規約](https://affiliate.amazon.co.jp/help/operating/agreement) から。とくに5章「乙がアソシエイトであることの表示」ができてない個人・企業のサイトが多くまた卑劣であることが主な理由です。
[^harmful]: これらはセキュリティーツールが行う仕事（しかも対応が早い）で、私が行動を起こすことはありません。