var ステートメントは変数( variable )を宣言<br>
関数の引数リストと同様に、複数の変数の最後に型を書くことで、変数のリストを宣言できる<br>

var ステートメントはパッケージ、または、関数で利用できます。例のコードで示す<br>

```
pakage main //パッケージを宣言

import "fmt" //fmtパッケージをイポート

var c, python, java bool　//varを宣言している

func main(){ //プログラムをコンパイルして実行すると、まず main パッケージの中にある main()関数が実行される
  var i int //　変数　iを定義している
  fmt Println(i, c, python, java)  //値を標準の書式で出力
}

出力結果
0 false false false
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

<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Named%20return%20values.md">前回</a>
