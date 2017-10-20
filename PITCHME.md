# Google から<br />褒められた話

---

あとで資料は共有します。 <br />
(github においてあります) <br />
技術の話より自慢話成分が多めです <br />

---

## 目次

* 自己紹介
* Google から褒められた話
* 何をやったのか
* TIM と受賞の関係
* まとめ

<small>ちょいちょい質問タイムをはさみます</small>

---

## 自己紹介

* 小宮 健
* SI部所属
* 2005年入社 (たしか)

---

## 自己紹介

* 2年半ぐらい常駐してます
    * いまは恵比寿で某案件を手伝ってます
* 最近はコードを書いていません (仕事では)
    * 老害化してたらそっと教えてください

---

## Google から褒められた話

* 褒められました
* Open Source Peer Bonus Program

---

## Open Source Peer Bonus Program

![Open Source Peer Bonus Program](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/OpenSourcePeerBonus_1.png?raw=true)

https://opensource.googleblog.com/2017/10/more-open-source-peer-bonus-winners.html
---

## Open Source Peer Bonus Program

![Open Source Peer Bonus Program](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/OpenSourcePeerBonus_2.png?raw=true)

https://opensource.googleblog.com/2017/10/more-open-source-peer-bonus-winners.html
---

## Open Source Peer Bonus Program

![Open Source Peer Bonus Program](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/OpenSourcePeerBonus_3.png?raw=true)

https://opensource.googleblog.com/2017/10/more-open-source-peer-bonus-winners.html

---

## Open Source Peer Bonus Program; FAQ

* Q. これなんなの?
* A. Googleが社外の OSS 開発者を褒める仕組み、だそうです。

> Google Open Source established this program six years ago to encourage Googlers to recognize and celebrate external contributors to the open source ecosystem Google depends on.

---

## Open Source Peer Bonus Program; FAQ

* Q. どうやって選ばれたの?
* A. Googleの社員がノミネートしてくれたようです。
  ある日メールが来て、受け入れるかどうか、Webに掲載してよいかを聞かれました。

---

## Open Source Peer Bonus Program; FAQ

* Q. 何かもらえたの?
* A. "a special thank you gift" がもらえるらしい <br />
  (まだもらっていない)

---

## Open Source Peer Bonus Program; FAQ

* Q. 日本人初だって?
* A. 違います。日本人っぽい名前だと 4人目みたい

---

## Open Source Peer Bonus Program; FAQ

* Q. すごいことを成し遂げたんでしょ?
* A. 違います。OSS 活動をこつこつやっていただけです。

---

## Open Source Peer Bonus Program; Q&A

* 他、質問があれば答えます

---

## 何を褒められたのか

![sphinx-doc.org](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/sphinx-doc.org.png?raw=true)

---

## Sphinx

* ドキュメント変換ツール
* マークアップされたテキストを HTML, PDF, EPUB などに変換する

![執筆フロー](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/sphinx-flow.png?raw=true)

## Sphinx

* 執筆には reStrucutredText を使う
    * 一応 markdown にも対応している (が中途半端)
* 元々は Python のドキュメント用に作られた
* 現在は言語を問わず、いろんな所で使われている

---

## Sphinxの利用事例

<!-- [Python documentation](https://docs.python.org/3/) -->
![docs.python.org](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/python.org.png?raw=true)

---

## Sphinxの利用事例

<!-- [Linux Kernel](https://www.kernel.org/doc/html/latest/) -->
![www.kernel.org/doc](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/kernel.org.png?raw=true)

---

## Sphinxの利用事例

<!-- [AWS CLI](http://docs.aws.amazon.com/cli/latest/index.html) -->
![AWS CLI](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/awscli.png?raw=true)

---

## Sphinxの利用事例

* [ansible](http://docs.ansible.com/ansible/latest/index.html)
* [chef](https://docs.chef.io/index.html)
* [Ubuntu Packaging Guide](http://packaging.ubuntu.com/html/)
* [Debian Policy Manual](http://www.debian.org/doc/debian-policy/)
* などなど

---

## Sphinxの利用事例

こういう見た目のページはだいたい Sphinx製 <br />
![readthedocs.org](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/readthedocs.org.png?raw=true)

---

## Sphinxの利用事例

* 弊社の案件でもいくつか使われています
* 使ったことある人?

---

## Sphinxで何をやっているのか

* Sphinx のメンテナのひとり
    * アクティブなのは数人
    * 作者は完全にフェードアウト

---

## Sphinxで何をやっているのか

* イシューの仕分け、回答
* バグの修正
* 新規機能の開発
* PR のレビュー
* リリース作業

---

## Sphinxで何をやっているのか

* まあ大体全部です
* べつに偉くはないです <br />
  (上下関係とか役職はない)

---

## Sphinxで何をやっているのか

[コミットの約60%](https://github.com/sphinx-doc/sphinx/graphs/contributors?from=2015-10-01&to=2017-10-01&type=c)は小宮によるもの (直近2年間) <br />
![コミットグラフ](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/commit_graph.png?raw=true)

---

## Sphinx; FAQ

* Q. なんでメンテナやってるの?
* A. なりゆき。ある時 Sphinx 本体に大きめの PR を投げたら権限もらえた。

---

## Sphinx; FAQ

* Q. メンテナって凄腕なんでしょ?
* A. 違います。
    * コードの構造と業務知識(各種フォーマットとか)を持っているだけ
    * 知らないところは仕様書とにらめっこ
    * 必要な知識が幅広すぎて苦労してる

---

## Sphinx; FAQ

* Q. 英語ペラペラなんでしょ?
* A. 違います。
    * Google翻訳のおかげです
    * ただ、2年もやってるので、簡単な文章の読み書きぐらいはできるようになった
    * もちろん喋れません。

---

## Sphinx; FAQ

* Q. なんでメンテナやってるの?
* A. 自分では使っていないし、あんまり前向きな理由はないかも。
    * 自分がやめると開発が止まるという責任感めいたものはある
    * プログラミングが好きなので、盆栽ワークとして

---

## Sphinx; Q&A

* 他、質問があれば答えます

---

# OSS メンテナの一日

---

## OSS メンテナの一日

* 朝
    * 電車でメールを読む
    * 返事を書くのはだるいので、だいたい読むだけ

---

## OSS メンテナの一日

* 昼
    * デスクでサンドイッチをかじりながら、メールを読む
    * 食べ終わったら、そのまま返事を書いたりバグを直したり
    * 昼休みが終わるまで繰り返す

---

## OSS メンテナの一日

* 仕事中
    * (仕事に余裕があれば) バグを修正する <br />
      <small>注) いまは時間で契約しているのでやってない</small>

---

## OSS メンテナの一日

* 夜
    * 帰りの電車でメールを読む
    * 自宅に帰って、ご飯を食べた後、バグを修正する

---

## OSS メンテナの一日

* 休みの日
    * 予定がない日は、自宅でコードを書いたり、喫茶店でコードを書いたり

---

## OSS メンテナの一日

* まとめ
    * だいたいメールを読むか、コードを書いてる
    * なぜならSphinxには600件を越すイシューが蓄積されているから！

![Sphinx has too much issues!](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/sphinx_has_too_much_issues.png?raw=true)

---

## OSS メンテナの一日

![イシューの増加傾向](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/increase-of-sphinx-issues.png?raw=true)

---

## 中間まとめ

* Sphinxのメンテナとしてそれなりに頑張って活動してます
* それなりに使われているみたいです
* Googleからお疲れ様、と褒められました

---

# TIM と受賞の関係

---

## TIM からの支援

* 関係ありません！僕の努力の結果です！

---

## TIM からの支援

* 関係ありません！僕の努力の結果です！
* …ではなくて、支援してもらっています。

---

## TIM からの支援

* 弊社には(間接的に)いくつか支援をしてもらいました
    * PCの貸与
    * PocketWiFi の貸与
    * 業務のスキマ時間 (黙認)
* あらためて、ありがとうございます

---

## TIM からの支援

* 思い返すと、これまでも他にも支援を受けてきました
    * 勉強会の開場提供
    * 勉強会の参加費支援 (交通費含む)
    * 書籍代

---

## TIM からの支援

* 勉強会の開場提供
    * Python mini Hack-a-thon (一時期)
    * Sphinx Hack-a-thon
    * Sphinx ハンズオン
    * アジャイルサムライ新宿道場
    * 継続的デリバリー読書会 (数回で挫折)
* 他にもやってる人いますね (読書会とか)

---

## TIM からの支援

* 勉強会の参加費支援
    * RubyKaigi
    * YAPC::Asia Tokyo
    * PyCon JP
    * その他たくさん

---

## TIM からの支援 (まとめ)

* 業務に関するものの転用(機材)
* 場所
* 時間
* 費用

---

## TIM からの支援

* 小宮だけが特別に支援を受けているわけではない
    * TIM の支援は社員であれば誰でも受けられる

---

## TIM からの支援

* 今年度の実績 (途中経過)
    * 書籍 116冊
    * 勉強会支援 35回
* 業務中の OSS貢献も現在検討中 (by 武藤)

---

## TIM はみんなの勉強を支援します

* 機材
* 勉強会/カンファレンス等の参加機会/費用
    * 交通費や宿泊費も支援するよ
    * 昼間のカンファレンスは業務扱いにするよ
    * 平日の勉強会に参加するための早抜けも ok
* 他、なにか支援が必要そうなもの

---

## TIM はみんなの勉強を支援します

* フィードバックは必須ではない
    * レポートとか書くのは大変だし、思ったほど読まれない
    * 参加したけど面白くないこともあるし…

---

## TIM はみんなの勉強を支援します

* でも、面白いことはみんなで共有したい
    * **できるだけ** でよい
    * 形式は問わない
    * 雑談、slack などなど
    * 業務に活かせそうなものは取り込めると、みんなハッピーに

---

## TIM はみんなの勉強を支援します

* 業務に直接関係ないものでも構いません
* IT っぽいものならなんでも ok
* 必要なものがあったら声を上げてください
* 業務に支障が出ない範囲であれば、いくらでも支援します

---

## TIM はみんなの勉強を支援します

* Q. なんで支援してるの?
* A. 人財w への投資です。
* A. 将来の技術への投資 <br />(AI, IoT, クラウド, 言語, フレームワーク, etc.)
* A. 仕事につながることもあります

---

## TIM はみんなの勉強を支援します

* 社長には、予算増額に ok をもらいました
    * まだ予算的には余裕がある? みたい
    * 利用が多くなってから、(必要があれば) ルールを考えます
* 迷ったら小宮・武藤に相談してください。背中を押します

---

## 最近(?)読んだ本の紹介

* すっごいスローペースで技術書を読んでます
* Book-a-thon
    * 月2回の読書会。都内のルノアールでもくもく読書

![Book-a-thon](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/bookathon.png?raw=true)

---

## 最近(?)読んだ本の紹介

* Real World HTTP
    * HTTP 0.9 から 2.0 までを紹介しつつ、HTTP とその関連技術を説明

![Real World HTTP](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/real_world_http.jpg?raw=true)

---

## 最近(?)読んだ本の紹介

* ハイパフォーマンス ブラウザネットワーキング
    * ブラウザとサーバ間の通信をいろんなレイヤから高速化する本
    * コードだけでできない実装のチューニングに役立つ

![ハイパフォーマンスブラウザネットワーキング](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/high_peformance_browser_networking.jpg?raw=true)

---

## 最近(?)読んだ本の紹介

* Re:VIEW+InDesign制作技法
    * マークアップされた原稿から紙面を制作するときの自動化テクニック
    * 泥臭いところが紹介されていて面白い

![Re:VIEW+InDesign制作技法](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/review_indesign_techs.jpg?raw=true)

---

## まとめの前の宣伝

* 最後にひとつだけ宣伝
* 明後日(10/20)に書籍が出ます

![Sphinxを始めよう 第2版](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/starting_sphinx.jpg?raw=true)

---

## まとめの前の宣伝 (おまけ)

![おまけ](https://github.com/tk0miya/tim-slide-20171020/blob/master/images/omake.png?raw=true)

---

## まとめ

* Google に褒められました
* Sphinxプロジェクトでやっていること
* TIMが支援してくれたこと
* 会社の脛をかじっていこう話

---

# Any questions?

---

## メモ

* [スライド(Git Pitch)](https://gitpitch.com/tk0miya/tim-slide-20171020/master?grs=github&t=black)
