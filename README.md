### lambdaについて

lambda式は「無名関数」とも呼ばれる関数でdef文と同じように関数を定義することができます。

また、1行に関数をまとめて定義できるので、簡単な処理などを定義するときにシンプルにまとめられます。</br></br>

では、まず基本的な構文を学びましょう。処理の概要としては下のように書きます。


>＞＞＞lambda 引数１,引数２,引数３, .... : 処理

lambda 関数では複数の引数を定義することができます。必要な引数はカンマで区切って記述します。

そしてコロンで区切って、処理を書くことで処理が戻されます。</br></br>


では、具体的な処理として、ユーロを円に両替するとき時の処理をdef文と比べながら書いてみましょう。
＊インタラクティブモードで実行します。</br>

＜def文＞
>＞＞＞def eur_ch_yen(eur,rate):</br>
...return eur* rate</br>
...</br>
＞＞＞eur_ch_yen(100,130)</br>
13000</br>

＜lambda式＞
>＞＞＞eur_ch_yen = lambda eur,rate:eur*rate</br>　
>＞＞＞eur_ch_yen(100,130)</br>
13000</br>

lambda式の文では、"eur"と"rate"というユーロと為替レートに対応する引数から"eur_ch_yen"という無名関数を定義しています。
定義した無名関数を2行目で、呼び出して引数をそれぞれ代入しています。</br></br>

これらはどちらも同じ処理をしていますが、lambda式の方が一度に文章を定義することができるのでdef文よりも行数が
短くなっています。
