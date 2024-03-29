




開発者はドキュメントを書くのをめんどくさがります。ですがドキュメントに明確な価値があると実感しているのも事実です。
では、明確な利益があるのにもかかわらず、ドキュメントを書くのは開発者から煙たがられるのでしょうか？



大半のエンジニアが持つ不満で最も多いと予測されるのが、**質の高いドキュメントの欠如**です。

ドキュメントに不満を持つときには次のような感想が出ると思います。

- 「このメソッドの副作用は何？」

- 「ステップ 3 の後でエラーが発生した...」

- 「この略語はどういう意味？」

- 「そもそもこの書類は最新？」

これは、Googleのソフトウェアエンジニアも例外ではありません。


歴史を俯瞰してみると、今のドキュメンテーションというプロセスの立場は1980 年代後半のソフトウェアの状態に似ています。

つまり、**「何か改善する価値がありそのために労力をかける必要があるが、それに対する組織的な認識はまだ働いていない」** という状態です。


これに対してGoogleで最も成功した取り組みは、**ドキュメントをコードのように扱い、従来のエンジニアリングワークフローに組み込むこと**です。
これにより、エンジニアが単純なドキュメントを簡単に作成および維持できるようにしました。


## ソフトウェア開発にドキュメントが必要な理由

まずそもそも、なぜドキュメントが必要なのでしょうか？

これに対するエンジニアの見解はほぼ一致しており、高品質のドキュメントはエンジニアリング組織に多大な利益をもたらします。

- コードとAPIがより理解しやすくなり、明らかに間違いが減ります。 

- 新しいメンバーを実践レベルに研修する手間が大幅に軽減されます。

- 設計目標とチームの目的が明確に示されているとやらなくていい作業が明確になります。

また、組織の財産という視点から見てもドキュメントという成果物を作るのには十分時間をかける価値があります。

それは、**ドキュメントは1回しか書かないかもしれませんがその後、何百何千回も読まれる**という事実にあります。
つまり、将来の開発者の数だけ価値が上がり、結果的に初期のコストを上回るのです。

ではなぜ、ここまで明確な利益があるのにもかかわらず、ドキュメントを書くのは開発者から煙たがられるのでしょうか？


## 開発者がドキュメントを書きたがらないわけ

エンジニアがドキュメントを書きたくない理由はいくらでも見つかります。

- エンジニアは、文章を書くスキルをプログラミングとは別のスキルと見なすことがよくあります。

- 一部のエンジニアは、自分は有能なライターではないと感じています。

- ツールのサポートや開発ワークフローへの統合が制限されている

- ドキュメンテーションを余分な負担、つまり保守する必要があるものと見なした

ですが、私個人はこれらよりももっと大きい理由があると思います。

それは、**ドキュメンテーションの利点はすべて必然的に下流にあるため、作成者にすぐに利益がもたらされない**という点です。

簡単にいうと、ドキュメントを書いても何も得しないと思っていることです。


## 開発者にとってのドキュメントを書く価値

### まともなドキュメントを書けるエンジニアは少ない

まず初めに、

**まともなドキュメントを書けるエンジニアは少ないです**

Twitterから引用しますと、以下のような声が挙がってます。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">ドキュメントを書けるエンジニア少ないのはすごく実感する。ドキュメントは開発をスケールさせることができる強力な武器なので、上手く活用するとエンジニア同士のコミュニケーションがなくなって開発効率上がるんだよね。伸ばすのが難しい能力 <a href="https://t.co/SgOrrPRcEF">https://t.co/SgOrrPRcEF</a></p>&mdash; pospome (@pospome) <a href="https://twitter.com/pospome/status/1539605902483144704?ref_src=twsrc%5Etfw">June 22, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">「優秀なエンジニア」の定義、各種仕様を理解しててコードが書けるってのはもちろんだけど、何よりコードと同じくらいドキュメントが書けるってのはかなり大切なんちゃうかなぁ<br><br>ドキュメントがないコードなんてただのゴミだし、自分が仕上げた仕事をちゃんと他人に伝えきることまでできれば一流かと</p>&mdash; コミさん (@komi_edtr_1230) <a href="https://twitter.com/komi_edtr_1230/status/1252551047349850113?ref_src=twsrc%5Etfw">April 21, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

ともすれば、「エンジニアはどんなプログラミング言語よりもまず日本語を読み書きできるようにするべきだ」という意見も。

エンジニアのコミュニケーション能力は度々話題に上がりますが、それは口頭だけでなく書面上でのやりとりを含むのかもしれません。

面接の場において、**XXプロジェクトでドキュメントを書きました！**と言えば少なくとも文章でのやりとりが可能なことの証明になりますね。

### ドキュメントを書くためにはスキルがいる

ドキュメントの作成にはツールを活用する会社があります。

例えば、javascriptのドキュメントの作成であれば、

- jsDoc

- doxygen

などのOSSライブラリーが活用できますよね。

あるいはソースコードとドキュメントが一体になったOSSライブラリも存在します（名前は忘れてしまいました...）

加えて、ドキュメントを書く際の文法も注意が必要です。
例えば、Markdownなどは書く際にどれだけ文法を深く知っているかで見栄えが変わります。

```md

##h2タグ

- 箇条書き

1. 箇条書き2

> 引用符

```

wikipediaのマークダウンの項目を見るとわかりますが、**以下全ての表記をマークダウンで表すにはそれなりの技量が必要になるのです。**

- 段落
- 改行
- テキストの強調
- コード
- リスト
- 見出し
- 引用
- リンク
- 水平線

https://ja.wikipedia.org/wiki/Markdown

これらのマークダウンを自由自在に操り思い通りの表現をすることは、開発者にとっても楽しい時間になるはずです。

### テクニカルライターという職種がある

Googleのソフトウェアエンジニアリングという本を読むまで知らなかったのですが、**テクニカルライターという職種がある**そうです。

参考になる方だと、こんなロールモデルがあります。

https://applis.io/posts/how-to-learn-technical-writing

```
テクニカルライティングの例としては、次のようなものがあります。

電子レンジの取扱説明書
APIリファレンス
社内の開発ドキュメント

こういった広い意味での製品について、利用者に分かりやすく伝えることがテクニカルライティングになります。
```

また、こんな求人を見つけました。

```md
【テクニカルライター】プロダクトナレッジ共有ドキュメント作成の求人・案件

【仕事内容】
・現場のエンジニア、マーケター、営業とコミュニケーションを取り、
　プロダクトのナレッジ共有のための
　ドキュメント作成をしていただきます。
・資料ユーザーのフィードバックを元に
　ドキュメント内容の改善にも携わっていただきます。

【求めるスキル】
・テクニカルライターとしての経験5年以上
・プロダクト開発において複数部署と
　横断的にコミュニケーションを取った経験
・ソフトウェア開発においての基本的な知見
・ビジネスレベルの英語力

【歓迎スキル】
・システム開発のご経験
・GitHubのご使用経験
```

https://freelance.levtech.jp/project/detail/52919/?utm_campaign=google_jobs_apply&utm_source=google_jobs_apply&utm_medium=organic

レバテックのようなエンジニア専用サイトでは、**ドキュメント作成のプロ**というポジションでも需要があることが伺えますね。




## 開発プロセスにとってのドキュメントを書く価値

- 多くの場合、ドキュメント自体を作成することで、エンジニアは設計上の決定を再評価することになります。したがって、**ドキュメントを書くことはAPIの定式化に役立ちます。**
説明も定義もうまくできない場合は、おそらくAPIの設計が十分ではありません。

- メンテナンスの変更履歴として活用できます。

- **他のユーザーからの質問が少なくなります。**これは、**ドキュメントを書いている人にとって時間が経過するとともに得られる最大の利点**です。そのソフトウェアについて誰かに2度説明しなければならない場合、そのプロセスは文書化するべきでしょう。

- コードがより洗練されたように見えます。例えばWebAPIを例に取ると、開発者は無意識のうちに「十分に文書化されたAPIがより適切に設計されたAPIである」と考える傾向にあります。
実際にその通りかどうかは置いておて、適切なドキュメントがあるかどうかは製品がメンテナンスされているかどうかを示す良い指標になるはずです。


これらの利点がドキュメントの作成者にとって大きいのと同様に、ドキュメントの利点の大部分は当然のことながら読者にももたらされます。





## 開発におけるドキュメントを書くメリット

title:開発におけるドキュメントを書くメリット

description:開発者はドキュメントを書くのをめんどくさがります。ですがドキュメントに明確な価値があると実感しているのも事実です。
では、明確な利益があるのにもかかわらず、ドキュメントを書くのは開発者から煙たがられるのでしょうか？

category_script:True









