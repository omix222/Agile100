# 非エンジニアの人から「アジャイルって早く作れるんでしょ？」って聞かれた時の私の一次回答

## 「アジャイルって早く作れるんでしょ？」

こんにちは。荒川です。

私はウイングアークの全社員（弊社は製販一体の会社なので、営業／マーケ部門、管理部門、開発部門などなど色々な人がいる）で横断的に構成された然るコミュニティなどにも所属したりしていまして、ソフトウェアの開発に携わっていない人とも幅広く関わらせていただいているのですが、先日いわゆる”非エンジニア”な仲間との雑談中にこんなことを聞かれました。

仲間「アジャイルって早く作れるんでしょ？」

私「う、うーん…（どう返答したらいいのだろう）」

しばらく言葉に詰まった私は、

私「ちょっと10分くらい時間もらって説明していいですか？」

と前置きしてその人にも伝わるようにアジャイルについて説明しました。
その内容をまとめたものが今回の記事です。


## 「早く作れる」とは何か？

「アジャイル」という言葉は本当に厄介（親しみを込めて）で、ちゃんと説明しようとするととても10分では説明できません。
もっというと私自身が全てを理論立てて説明できるとは言い切れない部分もあります。

したがって今回の説明については「早く作れるんでしょ？」の問いに対する答えだけに注力しました。
（アジャイルとアジャイル開発は違うだとか、アジャイルはプロセスじゃないとかそういったことはひとまず横に置いておきます）

まず私はその仲間に「早く作れる」の「早く」のイメージを確認しました。

* **とりあえず動く（バージョン0.1みたいな）状態のモノが早く完成するのか**
* **企画段階で盛り込んだ機能が全て備わっている（いわゆるバージョン1.0相当な）状態のモノが早く完成するのか**

仲間の回答は「後者」とのことでした。

やっぱりそうかと思った私は、夏頃の新人研修で使った資料を使いながら説明を開始しました。

## どっちのプロセスが正しいか

注：コチラ(https://flxy.jp/article/5984)の記事にもある通り「ウォーターフォールとアジャイルは対となる概念ではない」っていうことは踏まえた上で、あえて今回はウォーターフォールと対比しています。

![1.png](/images/chap-arakawa-ke/1.png?scale=0.5)

上下で違うプロセスを踏んで同じプロダクトが完成させたことを表した図です。
両プロセスとも一番右のプレゼントアイコンが完成品（バージョン1.0）であると認識ください。

そして仮定の話として、この完成品はとてもよく出来ていて、ビジネス的に大成功（売り上げがとても良い）と言えるクオリティのモノであるとイメージしてください。

さて「アジャイルが良いぞ、アジャイルが良いぞ」と言われて久しい昨今、どちらのプロセスが正しいと言えるでしょうか。

答えは、、

![2.png](/images/chap-arakawa-ke/2.png?scale=0.5)

そうです。どちらも正しいんです。

良いモノが作れるならウォーターフォールだろうがアジャイルだろうが、ここで例示していないやり方だろうがなんだっていいんです。

顧客に喜んでもらって儲かることが、われわれ民間企業の目的なわけですから。

![3.png](/images/chap-arakawa-ke/3.png?scale=0.5)

## じゃあなぜ多くの業界で「アジャイルが良さげ」的な空気になっているのか

アジャイルな動きが良いとされている一般的な理由についてまとめます。

### 「外部の変化に対応できる」という話

![4.png](/images/chap-arakawa-ke/4.png?scale=0.5)


### 「再現性」の話

![5.png](/images/chap-arakawa-ke/5.png?scale=0.5)

### 「収益が発生するタイミング」という話

![6.png](/images/chap-arakawa-ke/6.png?scale=0.5)

## アジャイルがなかなか定着しない理由

ここまで説明されると「うーんやっぱりアジャイルいいね」「アジャイルだといいモノ作れそう」となりそうですが、話はそんな単純ではありません。

前章までの説明で使用した各スライドの下部、すなわちアジャイルなプロセスの図は便宜上5つの輪っか（イテレーション≒繰り返し）でバージョン1.0が完成していますが、現実的にはもっとたくさんのイテレーションが必要となるでしょう。

![7.png](/images/chap-arakawa-ke/7.png?scale=0.5)

（この図を見せた時に非エンジニア仲間から「あ、そっか！」という反応をいただいたのは気持ちが良かった）

アジャイルはフィードバックを得る機会をたくさん作らないといけないため、開発に直結しない業務（プランニング、ふりかえり、レビューなどの非コーディング作業）の回数は増加し、確実にリードタイムは大きくなります。
そして本当に顧客に満足してもらえるクオリティに持っていけるまでの期間（輪っかの数）は未知なのです。

・・・

この時点でいったん「アジャイルって早く（完成形を）作れるんでしょ？」という仲間の問いに対する答えを伝えることが出来ました。

**答え：アジャイルはいつ完成するかわからないのです。**

これで当初の目的は達成できたわけですが、興が乗った私はもう少し話を続けました。

## アジャイルは面倒

要は、アジャイルは「良いモノを作れる確率を上げられるかもしれなくて」「早期から収益が見込めるかもしれない」けれども「開発業務以外の仕事が多くて」「開発スピードは上がらないであろう」シロモノであるということです。

私は日本の組織でアジャイルがいまいち定着しない理由は、プロセスの方法論ばかり注目されて、それ以前のアジャイルマインドの醸成の重要性が軽視されているからだと考えています。

* 自分の業務以外のタスクが多くて忙しくてなんかジレンマ
* あまり開発に集中できない
* 結果、開発スピードが上がらない

といった感じでアジャイルに悩む声を私はたくさん聞いてきましたし、私自身非常に共感しています。

## 面倒だけどやるという覚悟

ここまで説明したように、

「良いものが作れるかもしれない VS. 面倒くさい」

この図式で後者からの解放をとる組織が多い中、それでも前者を重んじアジャイルを採用したい場合どうすれば良いのでしょう。

まずは関係者全員が[アジャイルマニフェスト](https://agilemanifesto.org/iso/ja/manifesto.html)に書かれいてる内容を理解し、自分たちが作ろうとしているプロダクトにはアジャイルが必要だと納得している状態になる必要があると思います。

繰り返しになりますが、アジャイルは「短いイテレーションで少しづつ作る」「決められた行事（プランニング、ふりかえり、レビュー）をこまめにやる」といった**方法**ではありません。
アジャイルな開発を目指すには「アジャイルマニフェスト」とそこで謳われている価値や主義に基づいた12の原則を関係者全員が理解し実践する**状態**になる事を目指すという組織としての覚悟が必要となってきます。

こういったことからアジャイル界隈では有名な、
Don’t just do “Agile”, be “Agile”.
（アジャイルするな。アジャイルになれ）
という言葉があるんですね。

関係者全員が心技体でいう「心」の部分を理解しなければ、アジャイルは成り立たないのです。

> なので「それアジャイルで作る必要あるの？」と言った自身への問いかけもとても重要だと私は思っています。
> 作るモノ（完成形）は明らか、外部環境からの影響もない、それほどフィードバックも必要ない。
> そのようなモノは当初の企画通りに集中して作ってしまった方が、スピード、コスト、品質面でも成功の確度は高く、アジャイルが出る幕はありません。



## アジャイルになるには

まとめます。

* 「Don’t just do “Agile”, be “Agile”.」を関係者全員が理解する
* 「アジャイルは早く作れないし面倒くさいけど良いモノを作りたいからやる」という覚悟を関係者全員が持つ
* そのプロダクトの開発はアジャイルに進めた方が効果がある（ビジネスで勝てる）ことを関係者全員が納得している

この条件を満たして初めて組織はアジャイルなプロセスへの一歩を踏み出せるんだと思います。

・・・

仲間「なるほどですねー。」

私「むしろ『別にアジャイル開発とか意識してなくて、やるべきだと思った事をやってるだけなんだけどな』という組織の方が私からすればよっぽどアジャイルだったりするわけで…」

・・・という事を話そうとしたあたりでタイムアップ。
非エンジニア仲間への私のアジャイル語りは終了しました。

「全然思ってたのと違った。すごくよくわかった。」

と言ってくれたので嬉しかったです。

まあこの話はかなりデフォルメされていて多角的な視点にも欠けており、まだまだアジャイルの入り口にすぎないのですが…

その辺はまたおいおい語っていければと思います。

## 頑張って作ったものは売れて欲しいわけです

最後に私の立ち位置としては、

**「良いモノが作れるならね…最初は面倒かもしれないけどね…それぞれのプラクティスにはちゃんと理由はあるわけだから…見方とかマインドとか変化させて…みんなアジャイルになろうよ！」**

って感じです。

だって、

**「良いものが作れるかもしれない ＜ 面倒くさい」だからアジャイル嫌だ**

こんなの勿体無いじゃないですか。
日々頑張って作ったのに「お客さん喜ばない＆売れない」っていう事態は避けたいですよね。

**「良いものが作れるかもしれない ＞ 面倒くさい」だからアジャイルになってみよっかな！**

こうあるべきだと思います。
みんなの頑張りは報われるべきです、絶対。

## 小さなことから始めて、やがてアジャイルに…
今回の記事を読んで「大変そうだな」「何から始めたらいいかわからないや」などと思った方は、まずはイテレーションとかプランニングとかレビューなどは横に置いておいて、定期的な「ふりかえり」を極力コンパクトな期間で実施するだけでもアジャイルな組織に近づけると思います。

![8.png](/images/chap-arakawa-ke/8.png?scale=0.5)

![arakawake](/images/chap-arakawa-ke/arakawake.png?scale=0.2)

ウイングアーク１ｓｔでプロセス改善とソフトウェアテストの自動化に取り組んでます / Certified ScrumMasterR /Certified ScrumDeveloperR / JBA公認E級審判 / 全日本スノーダイビング協会会長
