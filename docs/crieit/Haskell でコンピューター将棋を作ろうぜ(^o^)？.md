# 前の記事

📖　[Haskell を Ubuntu にインストールできねーの（＾〜＾）？](https://crieit.net/posts/Haskell-Ubuntu)  

# 情報

📖　[kifuwarabe-shogi-haskell](https://github.com/muzudho/kifuwarabe-shogi-haskell)  

# はじめに

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　↓　コンピューター将棋では、Haskell を使ったのは、ながとダイアリーチームの Haskell将棋 というのがある」  

📖　[Haskell将棋](http://www2.computer-shogi.org/wcsc21/appeal/haskellshogi/hsShogiAppeal.htm)  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　ホームページが　リンク切れを起こしている」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　オープンソースにして　どこか管理団体が維持しないと　滅びるのよ」  

# Step 1.0

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　初手投了する将棋エンジンを作ろうぜ？」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　↓　リポジトリは作っておいたぜ」  

📖　[kifuwarabe-shogi-haskell](https://github.com/muzudho/kifuwarabe-shogi-haskell)  

```bash
gh repo clone muzudho/kifuwarabe-shogi-haskell
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　↑　このコマンド　どうやって使うんだっけ？」  

📂 `Home/Documents/git_hub`  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　↑　とりあえず　ローカルの置き場を決めましょう」  

```bash
cd ~/Documents/git_hub
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　↑　ターミナルで　そこへ移動」  

```bash
gh repo clone muzudho/kifuwarabe-shogi-haskell
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　↑　git hub のコマンドは前回インストール済みなので、そのままコマンドを打鍵、  
おっ、なにかクローンされた」  

```bash
code
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　↑　あとは　Visual Studio Code を使おう」  

```bash
muzudho@muzudho-MS-7B09:~/Documents/git_hub/kifuwarabe-shogi-haskell$ git commit -a
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	docs/

nothing added to commit but untracked files present (use "git add" to track)
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　↑　あれ？　`git commit -a`　コマンドが効かね？」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　`docs` フォルダーを追加したからじゃないか？」  

```bash
git add docs
git commit -a
# ここでメッセージを保存

git push
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　↑　おっ、いけた」  

.
