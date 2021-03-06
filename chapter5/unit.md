##単位法
　6つめのケアレスミスを防ぐテクニック **単位法** を紹介します．
ケアレスミスを防ぐテクニックはこれで最後です．

　単位法とは，単位があっているかを確かめる方法です．
単位法は数学の問題でも使えますが，化学や物理の問題でとても役に立つ方法です．

　単位には，m （メートル）, s （秒）, kg （キログラム）など，さまざまなものがあります．その中で，値を足し合わせることができるのは，同じ単位をもつ値のみです．$$1[\mathrm{m}] + 1[\mathrm{kg}] $$ という計算は意味がありません．

　そのため，式中で足し算・引き算を行なっている場合，それらが同じ単位でなければ間違っているとわかります．

　また，答えの値が正しい単位になっているかを確かめるということも有効です．

***

　しかし，単位を確かめようと思っても，複雑な式になっている場合はどうすれば良いでしょうか？

　例として，以下のような式を考えます．（等加速度運動の公式です）


$$
x = v_0t+\frac{1}{2}at^2
$$

単位 :　$$x [\mathrm{m}],\ v_0 [\mathrm{m/s}],\ a [\mathrm{m/s^2}],\ t [\mathrm{s}]$$

　この場合，$$v_0t$$ や $$\frac{1}{2}at^2$$ の単位を知らなくては確認できません．
実は，掛け算・割り算を行った値の単位は，単位を掛け算・割り算したものになるのです． $$v_0t$$ の場合は，
$$
[\mathrm{m/s}] \times [\mathrm{s}] = [\mathrm{m}]
$$
より，単位は$$[\mathrm{m}]$$となります．また，$$\frac{1}{2}at^2$$ の場合は，
$$
[\mathrm{m/s^2}] \times [\mathrm{s}] \times [\mathrm{s}] = [\mathrm{m}]
$$
より，単位は$$[\mathrm{m}]$$となります．
また，$$x$$ の単位も $$[\mathrm{m}]$$ なので，単位はすべて揃っていることがわかります．

***

　上の例のように値がすべて文字になっていればわかりやすいのですが，数字が混ざっている場合には注意が必要です．
たとえば，先ほどの式に， $$a=2$$ が代入された場合，

$$
x = v_0t+t^2
$$

となり， $$t^2$$ の単位が $$[\mathrm{s^2}]$$ のように見えてしまうからです．
そのため，数字が混じっている場合には，数を計算する前，もしくは代入する前に単位を確認することが重要です．
