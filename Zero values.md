変数に初期値を与えずに宣言すると、ゼロ値( zero value )が与えられる<br>
ゼロ値は型によって以下のように与えられる<br>

数値型(int,floatなど): 0
bool型: false
string型: "" (空文字列( empty string ))

```
数値型(int,floatなど): 0
bool型: false
string型: "" (空文字列( empty string ))

```

```
packge main //パッケージを宣言
import "fmt" 標準パッケージをインポート　(fmtパッケージをインポートしている)

func main(){ //プログラムをコンパイルして実行すると、まず main パッケージの中にある main()関数が実行される
  var i int //変数iを定義している　　varは定義　intはデータ型　
  var f float64　 //変数fを定義している
  var b bool //変数bを定義している
  var s string //変数sを定義している
  fmt.Printf("%v %v %v %q\n", i, f, b, s) 
}

出力結果
0 0 false ""
```
- 今回参考にしたサイト
<a href="https://golang.keicode.com/basics/go-data-types.php">参考サイト</a>
<a href="https://qiita.com/tenntenn/items/c55095585af64ca28ab5">参考サイト</a>

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

- 変数の定義
```
  func main(){ //プログラムをコンパイルして実行すると、まず main パッケージの中にある main()関数が実行される
  i := 2
  fmt.Println(i)  // 2が出力される
}
```
<a href="https://y-hiroyuki.xyz/go/variable/what-is-variable">参考サイト</a>


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

<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Basic%20types.md">前回　Basic types</a>

