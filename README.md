# GitをWindowsにDownload
Githubの登録とGitをwindowsで使えるようにしましょー  
結果的にgitコマンドを使えればokです。

Git for Windowsをインストール(すでにgitが使える人は不要)  
[Git for Windowsをインストール](https://gitforwindows.org/)
「Git Bash(アプリ)」が追加されます

GitHubのアカウントを作成(面倒であれば後で大丈夫)
[githubの登録](https://github.com/)

# リポジトリをローカルに持ってくる
「Git Bash」を立ち上げる  
コマンドでローカルのダウンロード場所に移動し、ファイルをDLします。
以下コマンド例  　
ドキュメントに移動  
`$ cd Documents`  
Graveファイルを作成  
`$ mkdir Grave`  
Graveファイルに移動  
`$ cd Grave`  
レポジトリからファイルをダウンロード  
`$ git clone XXXX`  
↑のXXXXは下記をコピー
<img src="./img_for_readme/git1.png">
<img src="./img_for_readme/git2.png">

#ローカルで開く
エクスプローラでドキュメント配下のGraveに移動
srcに格納されている「xxxx.html」をお好きなブラウザで開けば確認できます。

# 本題:app_graveの説明
## img_for_readmeファイル
readme用なので無視してください〜
## imgファイル
サイトに表示する画像を格納
## srcファイル
サイト用のhtmlファイルを格納
- login.html
ログインページ
- grave-top.html
ログイン後のページイメージ
- grave-list.html
お墓の一覧ページ
- grave-detail.html

# ToDo
404ページ作成
デザインの刷新
