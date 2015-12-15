###これは Git を練習するためのレポジトリです

Github に載せたいダイレクトリーに移って、次の命令を打ち込む：<br/>
`$ git init`

`$ git add .`

`$ git commit -m "二重引用符の中にメッセージを"`

`$ git remote add origin 「github　で作ったレポジトリのリンク先」`<br/>
(インターネットの何かにつながってないからそうしないといけない）

`$ git remote -v`（remote を 確認（verify）する）

`$ git push origin master`

レポジトリの作り方について以上です。

/---------------------------------------------------/

#Git に載せるには：

何を変えたか確認できる：<br/>
`$ git status`

新しいコードを追加して/変えてから、こう入力します：<br/>
`$ git add .`

`$ git commit -m "コミットの内容"`

`$ git push origin master`

終わり！



/---------------------------------------------------/

たまに `$ git pull 「レポジトリの名前」` を使うと vim に入る。<br/>
その場合には、`i` を押すとコミットを書いて、 `esc` を入力すると insert mode から出て、<br/>
`:wq` を入力するとコミットを保存して vim から出る。

/---------------------------------------------------/
