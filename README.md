# なにここ

私（STSynthe a.k.a. えむ）個人が手入れしている日本国内Adblock Plus用フィルターです。

元のABP Japanese filtersは短いフィルターによってパフォーマンス低下と誤爆が問題でした。さらにuBlock Originからは[「ABP Japanese filtersは酷い」と酷評され](https://www.reddit.com/r/uBlockOrigin/comments/apby98/default_included_abp_japanese_filters_just_sucks/)、デフォルトのリストから外されました。ついには2021年中期で止まってしまいました。

その問題を個人的に気になる部分を排除・最適化し、主に***自分用***として使っています。また長期でメンテすることはないです。そのようなモノでも良ければ、お試すのは自由です。

# 方針

* 短いフィルターになるべく頼らない
* テキスト広告を（誹謗、中傷、差別、などの目に余るほどでもなければ）排除しない
* エンターテイメント的な広告を排除しない（例：ニコニ広告、アニメなどの応援バナーなど、見かけなくなったけど…）

## 問題報告

このフィルターが引き起こしてる表示の乱れや動作不良の対応は[issues（問題報告）](https://github.com/STSynthe/abp-japanese-filters/issues)のみ受け付いてます[^1]。

* 【必須】問題を引き起こしてるウェブサイトURL（ウェブサイトのタイトルのみ記入不可）
* 表示の乱れや動作不良（あからさまなら記入不要）
* 本来の表示や動作（あからさまなら記入不要）
* 【必須】環境（OS、ブラウザ、拡張機能、購読してるフィルタなど）

を添えて投稿して下さい。

ABP Japanese filtersが抱えてる問題を潰すには私一人では難しいと考えてます。ご協力感謝します。

# 購読

ABP Japanese filtersとは別に

* [ABP filters](https://github.com/abp-filters/abp-filters-anti-cv) （GNU GPL v3.0）
* [EasyList](https://easylist.to) （GNU GPL v3.0 + CC BY-SA 3.0）

以上購読を推奨します。ただ別の日本国内用フィルターを組み合わせるのはあまりおすすめしません。***重たくなる原因***になります。

≫ <a href="abp:subscribe?location=https%3A%2F%2Fraw.githubusercontent.com%2FSTSynthe%2Fabp-japanese-filters%2Fmaster%2Fabpjf.txt">フィルターの購読（インストール）</a> ≪ - （[ソース](https://raw.githubusercontent.com/STSynthe/abp-japanese-filters/master/abpjf.txt)）

# 免責

* このフィルターを利用したことによる何らかの障害を受けた。
* 動作保証。
* issuesでの対応[^1]。

# Links

## my

* [Git](https://github.com/STSynthe/abp-japanese-filters)
* [コミットログ](https://github.com/STSynthe/abp-japanese-filters/commits/master)
* [stsynthe.github.io](https://stsynthe.github.io/abp-japanese-filters/)

## tools

* [Adblock Plus](https://adblockplus.org/) - 今の本家、重厚。
* [uBlock Origin](https://ublockorigin.com/jp) - ADPより身軽さをアピール。
* [Vivaldi ブラウザ](https://vivaldi.com/ja/) - フィルター内蔵の素晴らしいブラウザ。

## filters

* [ABP Japanese filters（本家）github.com/k2jp/abp-japanese-filters](https://github.com/k2jp/abp-japanese-filters)。GNU GPL v3.0 + CC BY-NC-SA 4.0。
* [豆腐フィルタ](https://github.com/tofukko/filter) - 2022年時点でも密かに更新が続いてる日本国内用フィルター。ソースが綺麗に整理されてる。コピーレフト？。
* [もちフィルタ](https://eeii0a5l.github.io/mochifilter_homepage/mochi.html) - 最低限のコモンで弾いてるためか、より軽量を唱っている。CC0らしい[^2]。
* [Yuki's uBlock Japanese filters （雪フィルタ）](https://github.com/Yuki2718/adblock) - uBlock Origin向けのフィルタ。CC BY-SA 4.0。

## others

* [フィルター構文 Adblock Plus](https://help.eyeo.com/adblockplus/how-to-write-filters) - メモ用。

[^1]: （2022年5月上旬時点）READMEにあるように主に自分用です。もちや雪のように外部の掲示板を立ててまで不具合対応するモチベーションはないです。ドネーションも今のところ考えてません。
[^2]: （2022年5月上旬時点）「もちフィルタは、EasyListと豆腐フィルタから必要最小限のフィルタを抜き出したもの」としてる。真偽は兎も角、[EasyListはライセンスを明確](https://easylist.to/pages/licence.html)にしている…