var 宣言では、変数毎に初期化子( initializer )を与えることができる<br>
初期化子が与えられている場合、型を省略<br>
その変数は初期化子が持つ型<br>

```
package main //パッケージを宣言
import "fmt" //fmtパッケージをイポート

var i, j int =1,2 // 変数i,jに1,2に代入してる

func main(){
  var c, python, java = true, false, "no!"
  fmt.Prinln(i, j, c, python, java))

出力結果
1 2 true false no!
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

- 関数の定義
```
func 関数名(){
 //処理内容
}
```

- main関数<br>
プログラムの最初に呼び出される関数<br>
<a href="https://zenn.dev/kubo_programmer/articles/990891ff3a43c5">参考サイト</a>

<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Multiple%20results.md">前回</a>
