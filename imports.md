- Goのプログラムは、パッケージpackageで構成<br>
- プログラムは main パッケージから開始<br>

このプログラムでは "fmt" と "math/rand" パッケージをインポート( import )している

```
package main //パッケージを宣言

import (　 //取り込む、、持ち込むという意味
    "fmt"　//　パッケージ
    "math/rand"//パッケージ　
)

func main(){　//main関数を実行するよ
  fmt.Println("My favorite number is",rand.Intn(10))
}

```

- package mein パッケージを宣言のこと<br>

- パッケージ<br>
Goには予め用意されている標準パッケージがあり、標準パッケージを利用する事で、<br>
プログラミングを効率良く行うための便利な機能 fmtパッケージはコンソールを出力するパッケージ<br>

- fmtパッケージ<br>
fmtパッケージは、主に文字列の入出力と、フォーマット(書式設定)に関する機能を提供するパッケージ<br>

- fmtパッケージの関数群<br>
Println関数は、標準出力への出力関数<br>
Println関数も同様に、デフォルトフォーマットで標準出力に書きこみますが、<br>
この際オペランドの間に半角スペースが入り、文字列の最後に改行が追加される

- math/randパッケージ<br>
math/randパッケージは疑似乱数生成器を実装するパッケージ<br>

<a href="https://github.com/morimotoyuuki111/Go2/blob/main/Hell%2CWeld.md" target="_blank" rel="noopener noreferrer">前回</a>
