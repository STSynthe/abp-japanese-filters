# 戯言

# uBlock Origin / AdGuardに対応してますか？

使えますが完動しません。<br>私が「スニペットフィルタ」と呼ばれるフィルタパターンを採用してから**非対応**になりました。

ここではフィルタ文の書き方について詳しく説明しませんが、Adblock Plusの基本フィルタで書いていれば他の広告ブロックツールもほぼ対応しています。ただ「スニペットフィルタ」と呼ばれる文法に違いがあるために非対応に成るということです。

現時点（2022年5月中旬）で他の広告ブロックツールに対応する考えはありません。コンバーターツールみたいなのを使えば解決すると思いますが、今はその時期ではないと考えています。敬遠ではなく、他とも仲良くやってく方向です。

# 本家にPullリクエストした方が今使ってる方々へ貢献できるのでは？

更新が絶え、なおかつ方針の違いによりしません。

* [github.com/k2jp/abp-japanese-filters/wiki/FAQ](https://github.com/k2jp/abp-japanese-filters/wiki/FAQ)
* [github.com/k2jp/abp-japanese-filters/wiki/Support_Policy](https://github.com/k2jp/abp-japanese-filters/wiki/Support_Policy)

# ポリシー云々の表示を消してほしい

ダメです。

ポリシー云々系は個人情報を収集している旨を閲覧者に必死でアピールしなければならないことを理解するべきです。

* プライバシーポリシーは「[個人情報の保護に関する法律](https://elaws.e-gov.go.jp/document?lawid=415AC0000000057)」に基づいて行われている。
* Cookieポリシーは「[一般データ保護規則（GDPR）](https://www.ppc.go.jp/enforcement/infoprovision/laws/GDPR/)」に基づいて行われる。

ここでは違いの詳しい説明をしませんが、「法令」による義務、「ペナルティー」による罰金があるため、「*必死でアピール*」になるのは必然です。

とばっちりを受けたくないのと、個人情報の収集停止を示すことができる、「広告」ではないため、どのみちこの件は無視しています。

# アマゾン アソシエイト（アフィリエイト）のリンクが消されている

単純な「広告」ではありますが、それ以上にアマゾンの規約に反するなど、それら多く見かけるようになりました[^amazon]。それらを総合的に判断し非表示を決定しました。

# YouTubeとか正しく見られるようになりましたか？

成りました。[#購読](#購読)にある推奨フィルタと合わせて使うのがベストです。

またYouTubeに限らず「広告」と関係ないモノを弾いてるフィルタは撤去していく考えです。

## 視聴履歴とかアノテーションとかは切ったままの方が良かった…

YouTubeの視聴履歴はプライバシー侵害にあたると疑問を抱くかと思ったり思わなかったりしますが、望みであればGoogle側の設定で履歴保持しない設定を自身でできるようになってます。そのようなモノをフィルタで弾くことはありません。

# 簿記

オチが良かったので、共有させてください。

* [twitter.com/ssig33/status/1094614899022426112](https://twitter.com/ssig33/status/1094614899022426112)

[^amazon]: [Amazonアソシエイト・プログラム運営規約](https://affiliate.amazon.co.jp/help/operating/agreement) から。とくに5章「乙がアソシエイトであることの表示」ができてない個人・企業のサイトが多くまた卑劣であることが主な理由です。