# PythonScope
スコープの理解

## 処理
変数の有効範囲を理解するため、それぞれに変数aを定義して確認する。

## コード
```
def sum(x, y):
    a = 5
    print("変数ａは" + str(a) + "です。")
    return x + y

a = 10
b = 20
gokei = sum(a, b)
print("変数ａは" + str(a) + "です。")
print("変数bは" + str(b) + "です。")
print("合計は" + str(gokei) + "です。")
```

## 出力結果  
```
変数ａは5です。
変数ａは10です。
変数bは20です。
合計は30です。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Python 3.6.4 |
