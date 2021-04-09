# unix-command-reference

UNIXベースのCLIを使用する際に、頻繁に用いるコマンドをまとめた一覧。


# ディレクトリ操作関連

ディレクトリの作成

```bash
mkdir ディレクトリ名
```


ディレクトリの移動

```bash
cd ディレクトリ名
```


一つ前のディレクトリに移動

```bash
cd ..
```


自分のホームディレクトリに移動

```bash
cd
```


ルートディレクトリに移動

```bash
cd /
```


ディレクトリの削除

```bash
rmdir
```


現在のディレクトリの確認

```bash
pwd
```


# ファイル操作関連

ファイル一覧の表示
```bash
ls
```


ファイルの内容を表示

```bash
more
```


ファイルのコピー（file1をfile2にコピーする）

```bash
cp file1 file2
```


ファイルの移動（file1をfile2に移動する）

```bash
mv file1 file2
```


ファイルの消去

```bash
rm ファイル名
```


# テキストエディタをCLI上で利用する

ディレクトリ内の当該ファイルを開く

```bash
vi ファイル名
```


閲覧モードから編集モードへ切り替え

* escキー


編集モードから閲覧モードへ切り替え

* iキー


viの終了

```bash
以下、編集モードで利用
:wq（ファイルを保存して終了）
:w ファイル名（ファイル名を指定して終了）
:q!（保存せずに強制終了）
```


# UNIX_OS上でC言語ファイルを扱う場合

* ファイル拡張子の付け忘れに注意


ファイルの作成

```bash
vi ファイル名.c
```


実行ファイルの作成（コンパイルリンク）

```bash
cc ファイル名.c
```


実行ファイルを実行

```bash
./a.out
```


# 参考資料

UNIXコマンド集
http://www.ritsumei.ac.jp/~tomori/unix.html

これだけは覚えておきたい！基本的なUNIXコマンド20【初心者向け】
https://techacademy.jp/magazine/6406