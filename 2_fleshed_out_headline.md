{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### lambdaについて\n",
    "\n",
    "lambda式は「無名関数」とも呼ばれる関数でdef文と同じように関数を定義することができます。\n",
    "\n",
    "1行に関数をまとめて定義できるので、簡単な処理などを定義するときにシンプルにまとめられます。\n",
    "\n",
    "では、まず基本的な構文を学びましょう。処理の概要としては下のように書きます。\n",
    "\n",
    ">lambda 引数１,引数２,引数３, .... : 処理\n",
    "\n",
    "lambda 関数では複数の引数を定義することができます。必要な引数はカンマで区切って記述します。\n",
    "\n",
    "そしてコロンで区切って、処理を書くことで処理が戻されます。\n",
    "\n",
    "\n",
    "では、具体的な処理として、ユーロを円に両替するとき時の処理をdef文と比べながら書いてみましょう。\n",
    "＊インタラクティブモードで実行します。\n",
    "\n",
    "＜def文＞\n",
    ">>>def eur_ch_yen(eur,rate):\n",
    "...return eur* rate\n",
    "...\n",
    ">>>eur_ch_yen(100,130)\n",
    "13000\n",
    "\n",
    "＜lambda式＞\n",
    ">>>eur_ch_yen = lambda eur,rate:eur*rate　\n",
    ">>>eur_ch_yen(100,130)\n",
    "13000\n",
    "\n",
    "\"eur\"と\"rate\"というユーロと為替レートに対応する引数から\"eur_ch_yen\"という無名関数を定義しています。\n",
    "\n",
    "どちらも同じ処理をしていますが、lambda式の方が行数が短くなっています。"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "anaconda-cloud": {},
  "kernelspec": {
   "display_name": "Python [conda root]",
   "language": "python",
   "name": "conda-root-py"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.5.2"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 1
}
