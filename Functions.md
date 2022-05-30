- 関数は、0個以上の引数を取ることができる<br>
この例では、 add 関数は、 int 型の２つのパラメータを取る<br>
変数名の 後ろ に型名を書くことに注意する<br>

```
package main//パッケージを宣言
import "fmt"//fmtパッケージをイポート

func add(x int, y int) int{  //add関数を定義して引数を２つ受け取り返す
  return x+y
}

func  main(){ //プログラムをコンパイルして実行すると、まず main パッケージの中にある main()関数が実行される
  fmt.Println(add(42,13))
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

- add関数<br>
2つの数値の合計を返す関数で演算子＋と同じ結果を返す<br>


- 関数の定義
```
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

<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Exported%20names.md">前回</a>
