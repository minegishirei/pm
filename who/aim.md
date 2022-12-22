


## 今の状況

エンジニアとしては割と順風満帆

ブランド力が欠如しているが...キャリアとしてはいい感じ


## 今後の目標

変わらず、**ブランド力**

<img src="https://prdx.co.jp/visions-prdx/wordpress/wp-content/uploads/2020/03/pdx_13_01.jpg">

そのためにやるべきこと

エンジニア,ブロガー,リクルーター
という三つのワードがあるが、
それを「世の中への役立ち方の約束」という形でまとめること
**テクニカルライター**

そして、「みねぎしれい」=その一つの言葉という方程式を作ること

最後に、それを宣言し、一気通貫で行動を起こすこと
**つまり、ルールを決めて実行すること**

- 自身の保有する技術について今後もわかりやすく丁寧な発信をしていきます

- 











## 職業:エンジニア,リクルーター,ブロガー

- エンジニア(5pt)
    1. アーキテクト
        - [docker](https://techblog.short-tips.info/docker/)
        - [Archtecture](https://techblog.short-tips.info/inhouse_se/)
        - [合意形成](https://pm.short-tips.info/communication/)
    2. コーディング
        - [Python](https://techblog.short-tips.info/python/)
        - [Django](https://techblog.short-tips.info/python/)
        - [Javascript](https://techblog.short-tips.info/javascript/)
        - [SQL](https://techblog.short-tips.info/sql/)
    3. タイピング
        - ショートカットキー
        - タイピング
        - 仮想デスクトップ
        - [Vim](https://techblog.short-tips.info/vim/)
        - 指トレ
        - HHKB
    4. マネジメント
        - [リファレンスドキュメント](https://pm.short-tips.info/culture/1217documentation.md)
        - [コードレビュー](https://pm.short-tips.info/culture/1040team.md)
        - 情報共有
        - [アジャイル](https://pm.short-tips.info/agile/1000inception_deck.md)
- ブロガー(1pt)
    1. 記事執筆
        - キーワード選定（キーワードプランナー）
    2. SEO対策
    3. サイト改善(セミナー等参加)
        - 既存ページの改修
    4. ツール使用
        - Google Search Console
        - Google Analytics
    5. マネタイズ
        - Adsense
- リクルーター(2pt)
    1. 求人サイトの構築と求人動向分析
        - [FlameValue(プログラミング言語ランキングサイト)](https://flamevalue.short-tips.info/)
        - [講演会実施](https://twitter.com/goofmint/status/1587353125827944448)
    2. 記事作成
        - careerブログ





突然ですがシステムのアーキテクチャスタイルを7つ全て言えますか？
コードレベルのデザインついての知識を持っていたとしても、アーキテクチャレベルの知識を持っている人はほとんどいないと思います。
例えば、シングルトンという名前を知っている人でもスペースベースアーキテクチャを知ってる人は少ないでしょう

このスレッドで全て解説します

#駆け出しエンジニア

---

また、今後も定期的にアーキテクチャに関する情報をTwitterやブログで発信していきます。ぜひフォロー、リツイートお願いします。

---

まずそもそもどんなアーキテクチャが世の中にあるのでしょうか。
アーキテクチャの一覧はこちらにありますが、念の為次のスレッドで一覧表示します。


#駆け出し
https://techblog.short-tips.info/inhouse_se/2000software_arc.md

---

これがアーキテクチャスタイルの一覧です。

巨大な泥団子
レイヤードアーキテクチャ
パイプラインアーキテクチャ
マイクロカーネルアーキテクチャ

サービスベースアーキテクチャ
イベント駆動アーキテクチャ
スペースベースアーキテクチャ
マイクロサービスアーキテクチャ

---

まず、巨大な泥団子についてですがこれについて言及することはありません。

クラスの変更の余波の予測が困難になり、関心ごとを分離することができなくなった最悪のアーキテクチャです。迷わず回避しましょう。

https://techblog.short-tips.info/inhouse_se/2000software_arc.md#4

---

さて、レイヤードアーキテクチャについてですが、このアーキテクチャはシンプルさや親やすさ、コストの低さからほとんどのアプリケーションのスタンダードの形となっています。
とにかく安く小規模ならばこれで良いでしょう

https://techblog.short-tips.info/inhouse_se/2001layerd_arch.md


---

プラグインアーキテクチャの用途は大きく分けて2種類あり、

パッケージ化され、単一のモノシリックなアプリとしてダウンロードされてインストールできるようなアプリケーション

カスタムビジネス(国ごとのローカライズが発生するなど)アプリケーション

このいずれかで使用される。

https://techblog.short-tips.info/inhouse_se/2003micro_kernel.md


---


スペースベースアーキテクチャの特徴は、アプリの標準的なトランザクションに中央のデータベースが関与しないことです。 これにより、データベースのトランザクションというボトルネックが解消されアプリケーションのスケーラビリティは無限になります。

https://techblog.short-tips.info/inhouse_se/2006space_base_arch.md


---

イベント駆動アーキテクチャは高度にスケーラブル(弾力性が高い)で高パフォーマンスなアプリケーションを実現できるアーキテクチャです。

https://techblog.short-tips.info/inhouse_se/2005event_driven_arch.md


---

サービスベースアーキテクチャは、マイクロサービスアーキテクチャの要素もある、分散型のアーキテクチャだ。
しかし、マイクロサービスやイベント駆動のタイプに見受けられる複雑さやコストがなく、多くのビジネスアプリケーションで選択されています。

https://techblog.short-tips.info/inhouse_se/2004service_base_arch.md

---

マイクロサービスのコアな価値観は疎な結合による高度な分離です。 各サービスでは、会社がやりたい事業をそのままシステム化しています。

https://techblog.short-tips.info/inhouse_se/2008microservice_arch.md


---

パイプとフィルターのそれぞれの一方向性とシンプルさは、構成の再利用を促します。

https://techblog.short-tips.info/inhouse_se/2002pipline_arch.md

---

以上の7+1の8種類が基本となるアーキテクチャです。
システムのリプレイスや新規設計の際に考慮に入れてみてください。
それでも、どのようにリプレイスすればいいか分からなければこの記事から遡ると良いでしょう。

https://techblog.short-tips.info/inhouse_se/2045_0why_module.md

---

以上です！お疲れ様でした！
くどいようですがフォロー,リツイート等お願いします。









