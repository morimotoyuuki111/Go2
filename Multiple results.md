関数は複数の戻り値を返すことができる<br>
swap 関数は2つの string を返す<br>

```
package main //パッケージを宣言
import "fmt" //fmtパッケージをイポート

func swap(x,y string)(string,string) {　//swap関数を定義して2つのstringを返している
  return y,x
}

func main(){ //プログラムをコンパイルして実行すると、まず main パッケージの中にある main()関数が実行される
  a,b := swap("Hello","Wold") //返された文字
  fmt.Println(a,b)//値を標準の書式で出力
}

Wold Helloと出力される
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

- swap関数<br>
複数の戻り値を戻す関数<br>
- func　関数名で関数の宣言を行う<br>
- ()内には引数を指定しますが今回の内容では、引数は使用しないので、()の中は空のままにしておく<br>
- 2行目の関数の処理内容は関数を呼び出しを行った際に実行される<br>

- main関数<br>
プログラムの最初に呼び出される関数<br>
<a href="https://zenn.dev/kubo_programmer/articles/990891ff3a43c5">参考サイト</a>

<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Functions%20continued.md">前回</a>
