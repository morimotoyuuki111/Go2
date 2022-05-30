Goでの戻り値となる変数に名前をつけることができる<br>
戻り値に名前をつけると、関数の最初で定義した変数名として扱われる<br>
この戻り値の名前は、戻り値の意味を示す名前とすることで、関数のドキュメントとして表現するようにする<br>
名前をつけた戻り値の変数を使うと、 return ステートメントに何も書かずに戻すことができる<br>
これを "naked" return と呼ぶ<br>
例のコードのように、naked returnステートメントは、短い関数でのみ利用する<br>

```
pakcage main //パッケージを宣言
import "fmt" //fmtパッケージをイポート

func split(sum int) (x,y int) { //split関数を定義
  x = sum * 4 / 9
  y = sum - x
  return
}

func main(){ //プログラムをコンパイルして実行すると、まず main パッケージの中にある main()関数が実行される
  fmt.Println(split(17))//値を標準の書式で出力
}
```

- package main<br>
 パッケージを宣言のこと<br>
 
- パッケージ<br>
 Goには予め用意されている標準パッケージがあり、標準パッケージを利用する事で、プログラミングを効率良く行うための便利な機能<br>
 ※fmtパッケージはコンソールを出力するパッケージ※<br>
  
- インポート　<br>
取り込む、持ち込む、などの意味<br>
 
- func main<br>
 メイン関数という意味<br>
    
- 関数<br>
関数とは複数の処理をまとめておくこと<br>

- split関数
文字列を特定の文字列で分割する関数

- 関数の定義
```
文字列を特定の文字列で分割する
func 関数名(){
 //処理内容
}
```
- func　関数名で関数の宣言を行う<br>
- ()内には引数を指定しますが今回の内容では、引数は使用しないので、()の中は空のままにしておく<br>
- 2行目の関数の処理内容は関数を呼び出しを行った際に実行される<br>

- main関数<br>
プログラムの最初に呼び出される関数<br>
<a href="https://zenn.dev/kubo_programmer/articles/990891ff3a43c5">参考サイト</a>

- 引数<br>
引数とは、関数に渡す値<br>
引数を使用する場合は「func 関数名(引数名 型)」と記述する事で、引数を呼び出し先の値<br>

- int型<br>
変数の種類<br>
point整数を入れられる<br>
point桁数が大きくなるときはlong型を使う<br>
<a href="https://wa3.i-3-i.info/word14966.html">参考サイト</a>

<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Multiple%20results.md">前回</a>
