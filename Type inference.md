明示的な型を指定せずに変数を宣言する場合( := や var = のいずれか)、変数の型は右側の変数から型推論される<br>
右側の変数が型を持っている場合、左側の新しい変数は同じ型<br>

```
var i int
j := i // j is an int
```
右側に型を指定しない数値である場合、左側の新しい変数は右側の定数の精度に基いて int, float64, complex128 の型になる<br>

```
i := 42           // int
f := 3.142        // float64
g := 0.867 + 0.5i // complex128
```

```
package main　　//パッケージを宣言
import "fmt"
func main(){　標準パッケージをインポート　(fmtパッケージをインポートしている)
  v := 0.345 + 0.34 //　　変数vに　0.345 + 0.34の方が代入される
	fmt.Printf("v is of type %T\n", v) //右側のvに型が代入されており％Tに埋め込まれている
  
  出力結果
  v is of type complex128
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

- 型推論<br>
<a href="https://www.nttdata.com/jp/ja/data-insight/2014/071001/">参考サイト</a>

- float64<br>
小数点型で小数点以下の扱える桁数が大きい<br>

- complex128型<br>
<a href="https://qiita.com/intelf___/items/039eccffd422321ec6dd">参考サイト</a>


<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Type%20conversions.md">前回　Type conversions</a>


