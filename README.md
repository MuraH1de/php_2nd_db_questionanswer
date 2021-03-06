## ①課題内容（どんな作品か）

前回のアンケートをDBで作成しました。

【ファイル概要】
- ```question.php```  <br>
    ⇒好きな競技を選択する
- ```second.php```  <br>
    ⇒選んだ競技の投票数をDB上でカウントする（UPDATE）<br>
    ⇒選んだ競技の名称、人気順を表示する。（SELECT）<br>
    ⇒思い出、ニックネーム、メールアドレスをDBに登録する。（INSERT）
- ```result.php```  <br>
    ⇒最終結果として、ニックネーム、何人同じ競技が好きと選択したか表示。 （SELECT）<br>
    ⇒過去に登録されたもの含め、思い出を表示。（SELECT）


【動作】
1. ```question.php``` で好きな競技を選んで「回答！」ボタンを押す
2. ```second.php```　で必要事項を記入して「送信！」ボタンを押す
3. ```result.php```最終結果表示


## ②工夫した点・こだわった点

- 前回、```jsonファイル、csvファイル```に入出力させたものを、DBで作成しました。
- 順位を表示させるときに、DBでソートさせるのではなく、配列に代入させてからソートしました。

## ③質問・疑問（あれば）

- ソートする際に、データ数が多くなかったので配列に代入させてソートさせたのですが<br>
  DBでソートする方とどちらがいいなど、経験上ありますでしょうか？？

## ④その他（感想、シェアしたいことなんでも）

データの件数をカウントする方法に```count```を使いました。
他にもSQLの関数を使えば幅が広がりそうなので、勉強してみます。
