# awesome-software-design-ja

[heynickc/awesome-ddd](https://github.com/heynickc/awesome-ddd)に触発されて作った日本語でのソフトウェア開発・設計に関する記事や書籍をまとめたリポジトリです。

良い記事などありましたらプルリク下さい！

## オブジェクト指向

- [オブジェクト指向でなぜ作るのか 第3版](https://www.nikkeibp.co.jp/atclpubmkt/book/21/S00180/)
- [オブジェクト指向入門 第2版 原則・コンセプト](https://www.shoeisha.co.jp/book/detail/9784798111117)
- [オブジェクト指向入門 第2版 方法論・実践](https://www.shoeisha.co.jp/book/detail/9784798111124)

記事・スライド

- [オブジェクト指向できていますか？](https://www.slideshare.net/MoriharuOhzu/ss-14083300)

## DDD

筆者の肌間ではありますが、実務で直接使わずとも知っておくだけで違うと思います。

### 記事・スライド

- [RoRやLaravelなどのフレームワークを使ってきた人がScalaを導入した時に引っかかる点とその解決策](https://qiita.com/sonken625/items/80c0d86d507dedcc654b)
  - [DDDを把握する](https://qiita.com/sonken625/items/80c0d86d507dedcc654b#dddを把握する)
- [scala-on-ddd](https://speakerdeck.com/crossroad0201/scala-on-ddd?slide=69)
- [Laravelでドメイン駆動設計(DDD)を実践し、Eloquent Model依存の設計から脱却する](https://qiita.com/mejileben/items/302a9f502ca0801b1efb)
  - [LaravelにDDDを導入して1年経った所感(達成したこと / 課題点 / モデリングの難しさなど)](https://qiita.com/mejileben/items/348d70e28fdbb3a0749f)
- [「実践ドメイン駆動設計」を読んだので、実際にDDDで設計して作ってみた！](https://qiita.com/APPLE4869/items/d210ddc2cb1bfeea9338)
- [かとじゅん氏のSpeaker Deck](https://speakerdeck.com/j5ik2o/)
- [ミノ駆動氏のQiita](https://qiita.com/MinoDriven)
- [広木 大地氏のQiita](https://qiita.com/hirokidaichi)
- [増田 亨氏のslideshare](https://www.slideshare.net/masuda220)
  - [ドメイン駆動設計 本格入門](https://www.slideshare.net/masuda220/ss-137608652)
  - [オブジェクト指向プログラミングのためのモデリング入門](https://www.slideshare.net/masuda220/ss-68667449)
  - [ドメイン駆動設計のためのオブジェクト指向入門](https://www.slideshare.net/masuda220/ss-57352072)
- [かとじゅんの技術日誌](https://blog.j5ik2o.me/)
- [little hands' lab ドメイン駆動設計を布教したい](https://little-hands.hatenablog.com/)
  - [DDD質問箱](https://peing.net/ja/little_hands)
  - [little-hands/ddd-q-and-a](https://github.com/little-hands/ddd-q-and-a)
- [ひろどらチャンネル](https://www.youtube.com/channel/UCUtQx4Gkpuy41wzyGjsHOwg)
  - [ぶっつけ本番でモデリングしてみる配信](https://www.youtube.com/watch?v=vEPS6QfPLII)
  - [【初めてゲストが来たよ】勝手にDDD #4 【かとじゅんさん】](https://www.youtube.com/watch?v=BBQzlIhz2N0&t=7062s)
- [集約の実装について考えてみた](https://zenn.dev/takashi_onawa/articles/4648332c035d97)
- [集約の境界と整合性の維持の仕方に悩んで2ヶ月ぐらい結論を出せていない話](https://kbigwheel.hateblo.jp/entry/2018/12/03/aggregate-and-consistency)
- [ドメインもしくはドメインモデルという概念が登場する書籍一覧](https://zenn.dev/j5ik2o/articles/333f92ab5db8eb24035f)
- [CQRS/Event Sourcingを学ぶための教材(2020年版)](https://zenn.dev/j5ik2o/articles/d9ab33e4da4408925bb6)
- [Martin Fowler's Bliki (ja)](https://bliki-ja.github.io/)

以下、筆者の独断で段階別に書籍を羅列させて頂きました。

### 初級

- [ドメイン駆動設計 モデリング/実装ガイド - little-hands - BOOTH](https://little-hands.booth.pm/items/1835632)
- [ドメイン駆動設計 サンプルコード&FAQ](https://little-hands.booth.pm/items/3363104)
- [わかる！ドメイン駆動設計 ～もちこちゃんの大冒険～【C91新刊】](https://booth.pm/ja/items/392260)
- [ドメイン駆動設計入門 ボトムアップでわかる！ドメイン駆動設計の基本](https://www.shoeisha.co.jp/book/detail/9784798150727)

### 中級

- [エリック・エヴァンスのドメイン駆動設計](https://www.shoeisha.co.jp/book/detail/9784798126708)
- [Domain Driven Design（ドメイン駆動設計） Quickly 日本語版](https://www.infoq.com/jp/minibooks/domain-driven-design-quickly/)

### 上級

- [実践ドメイン駆動設計](https://www.shoeisha.co.jp/book/detail/9784798131610)

### モデリング

- [ユースケース駆動開発実践ガイド](https://www.shoeisha.co.jp/book/detail/9784798114453)
- [モデルベース要件定義テクニック](https://www.shuwasystem.co.jp/book/9784798039442.html)

記事・スライド

- [混在したモデリングパラダイムの中で学ぶ重要なこと](https://qiita.com/j5ik2o/items/7ee00cfb22154efbab55)
- [ドメインオブジェクトの責務について](https://qiita.com/j5ik2o/items/a64007c6d7a89ec2e086)
- [TM（T字形ER）によるモデリング](https://www.sea.jp/Events/symposium/ss2009/contents/07-Modeling/ss2009-modeling-slide-tokimoto.pdf)

## クリーンアーキテクチャ

DDDとクリーンアーキテクチャは別物という認識です。

こちらの動画でその解説がなされています。

[READYFORエンジニアセッション Vol.3 「DDD:ドメイン駆動設計 入門〜はじめの一歩」](https://www.youtube.com/watch?v=03lDC8s0S5U)

記事・スライド

- [5年間 Laravel を使って辿り着いた，全然頑張らない「なんちゃってクリーンアーキテクチャ」という落としどころ](https://zenn.dev/mpyw/articles/ce7d09eb6d8117)
- [Laravelで実践クリーンアーキテクチャ](https://qiita.com/nrslib/items/aa49d10dd2bcb3110f22)
- [関心の分離を意識してサーバーを作ってみる(TypeScript + Express)](https://qiita.com/sadnessOjisan/items/ea5590efa3f55ef56edd)

書籍

- [Clean Architecture 達人に学ぶソフトウェアの構造と設計](https://www.kadokawa.co.jp/product/301806000678/)
- [iOSアプリ設計パターン入門](https://peaks.cc/books/iOS_architecture)

## システム設計

- [現場で役立つシステム設計の原則 〜変更を楽で安全にするオブジェクト指向の実践技法](https://gihyo.jp/book/2017/978-4-7741-9087-7)
- [ライティングソフトウェア](https://www.shoeisha.co.jp/book/detail/9784798166834)
- [セキュア・バイ・デザイン](https://book.mynavi.jp/ec/products/detail/id=124056)

記事・スライド

- [ビジネス考えてるかい？事業の持続的成長を促進させるシステム設計の考え方](https://speakerdeck.com/minodriven/buisiness-purpose-system-design)

## マイクロサービス

- [モノリスからマイクロサービスへ ――モノリスを進化させる実践移行ガイド](https://www.oreilly.co.jp/books/9784873119311/)
- [マイクロサービスパターン 実践的システムデザインのためのコード解説](https://book.impress.co.jp/books/1118101063)
- [データ指向アプリケーションデザイン ――信頼性、拡張性、保守性の高い分散システム設計の原理](https://www.oreilly.co.jp/books/9784873118703/)
