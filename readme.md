###これは Git を練習するためのレポジトリです

Github に載せたいダイレクトリーに移って、次の命令を打ち込む：<br/>
`$ git init`

`$ git add .`

`$ git commit -m "二重引用符の中にメッセージを"`

`$ git remote add origin` 「github　で作ったレポジトリのリンク先」<br/>
(インターネットの何かにつながってないからそうしないといけない）

`$ git remote -v`（remote を 確認（verify）する）

`$ git push origin master`

レポジトリの作り方について以上です。

/---------------------------------------------------/


たまに `$ git pull 「レポジトリの名前」` を使うと vim に入る。<br/>
その場合には、`i` を押すとコミットを書いて、 `esc` を書くと insert mode から出て、<br/>
`:wq` を入力するとコミットを保存して vim から出る。