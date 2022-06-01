```
pakcge main
import (
  "fmt"
)

func main() { //パッケージを宣言
 var func main() { 標準パッケージをインポート　(fmtパッケージをインポートしている)
 var x, y int = 3, 4 //変数x、変数yを定義している　xが３、yが４
	
 var f float64 = float64(x*y)*0.01 // 型変換しないとエラーになる　　
 mt.Println(f) // 0.12　　//float64(x*y)*0.01の計算結果がPrintln(f)に代入される
	
 var z uint = uint(f)　　zがどうしてもuintでなければならない時に、型変換 uint(f) を行う
 fmt.Println(x, y, z) // 3, 4, 0　　zの中に型変換した数値が出力されるため0.12の切り捨てられた０が入る//小数→整数に型変換すると、小数点以下は切り捨てられるので、0となる
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

- 変数の定義
51
```
  func main(){ //プログラムをコンパイルして実行すると、まず main パッケージの中にある main()関数が実行される
  i := 2
  fmt.Println(i)  // 2が出力される

}
```
<a href="https://y-hiroyuki.xyz/go/variable/what-is-variable">参考サイト</a>

- float64<br>
小数点型で小数点以下の扱える桁数が大きい<br>

-var z uint = uint(f)　　zがどうしてもuintでなければならない時に、型変換 uint(f) を行う<br>

- uint型
符号なし整数型とは、整数を格納するデータ型の一種で、0と正の数のみを表現できる整数型。 単純に全ビットを2進数の各桁に対応付けて数を表す。
