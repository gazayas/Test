###これは Git を練習するためのレポジトリです

Github に載せたいダイレクトリーに移って、次の命令を打ち込む：<br/>
`$ git init`

`$ git add .`

`$ git commit -m "二重引用符の中にメッセージを"`

`$ git remote add origin 「githubで作ったレポジトリのリンク先」`<br/>
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

/---------------------------------------------------/

####SSH を使って、`push` する時はユーザー名とパスワードを入力しないようにする
レポジトリーの github のメインページに, <br/>
HTTPS と SSH のいずれかを選択できるオプションがある。</br>
SSH の方を選択してください（SSH を作ってないないなら、最初はそれをして github に SSH を追加する必要がある）

そのリモートを git に追加する
`$ git remote set-url origin git@github.com:ユーザー名/レポジトリー名.git`


終わり！

/---------------------------------------------------/

たまに `$ git pull 「レポジトリの名前」` を使うと vim に入る。<br/>
その場合には、`i` を押すとコミットを書いて、 `esc` を入力すると insert mode から出て、<br/>
`:wq` を入力するとコミットを保存して vim から出る。

/---------------------------------------------------/
