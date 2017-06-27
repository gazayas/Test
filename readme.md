First, go to the directory you want to use git with and type this:

`$ git init`

`$ git add .`

`$ git commit -m "Type your message in here"`

`$ git remote add origin` -> After the word origin, type in the link to the GitHub repository

`$ git remote -v` -> Check out the remote you added

`$ git push origin master` -> Push your changes to GitHub

/---------------------------------------------------/

The flow for whenever you make changes:

`$ git status` -> Check out the status of the project

`$ git add .`

`$ git commit -m "message here"`

`$ git push origin master`

That's it!

/---------------------------------------------------/

Adding an SSH key so you don't have to type in your user name and password whenever you push to GitHub<br/>
[Checking for existing SSH keys](https://help.github.com/articles/checking-for-existing-ssh-keys/)<br/>
[Generating a new SSH key and adding it to the ssh-agent](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)
[Adding a new SSH key to your GitHub account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

### これは Git を練習するためのレポジトリです

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

# Git に載せるには：

何を変えたか確認できる：<br/>
`$ git status`

新しいコードを追加して/変えてから、こう入力します：<br/>
`$ git add .`

`$ git commit -m "コミットの内容"`

`$ git push origin master`

/---------------------------------------------------/

#### SSH を使って、`push` する時はユーザー名とパスワードを入力しないようにする
レポジトリーの github のメインページに, <br/>
HTTPS と SSH のいずれかを選択できるオプションがある。</br>
SSH の方を選択してください（SSH を作ってないなら、最初はそれをして github に SSH を追加する必要がある）

そのリモートを git に追加する<br/>
`$ git remote set-url origin git@github.com:ユーザー名/レポジトリー名.git`


終わり！

/---------------------------------------------------/

たまに `$ git pull 「レポジトリの名前」` を使うと vim に入る。<br/>
その場合には、`i` を押すとコミットを書いて、 `esc` を入力すると insert mode から出て、<br/>
`:wq` を入力するとコミットを保存して vim から出る。

`$ git rebase master`もやってみた`


/---------------------------------------------------/
