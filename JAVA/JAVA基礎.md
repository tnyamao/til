# インターフェースと抽象クラス

---

のまえに、、

### 継承

元の親クラスは１つ。
クラス（オブジェクト）を元に、より限定的（専門的）な機能を備えたオブジェクトを作る。

- 親クラス

<pre>
class Human {
  String name:
  eat () {}
  sleep () {}
}
</pre>

- 子クラス

<pre>
Class programer extends Human {
  progiraming () {
  }
}
</pre>


---

### インターフェース

何らかの機能だけを抽出したような存在
オブジェクトから分離した状

<pre>

Class Human implenemts runable, swimable, flayable {

}

</pre>

インターフェースは複数を実装できる

<pre>
Interface falyable {
  void fly();
}

</pre>

メソッドはfly() のみで、中身は空。
具体的な処理の中身は、その場で定義せず、実装先のクラスで定義する。

