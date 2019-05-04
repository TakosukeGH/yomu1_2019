# 読ム-１グランプリ

読ム-１グランプリの特設サイトです。


## サイト構築手順

> 分からないことがありましたら[@takosuke_tw](https://twitter.com/takosuke_tw)まで連絡下さい。

必要なのは以下の3つです。

- Githubアカウント
- netlifyアカウント(Githubアカウントでログイン可能)
- Hugo

まずは以下のURL等を参照して、Githubアカウントを作成して下さい。

- [【2019年1月現在】GitHubアカウント作成方法](https://qiita.com/okumurakengo/items/848f7177765cf25fcde0)

次に、読ム-1のサイトデータをコピーします。
以下のURLから読ム-1のリポジトリにアクセスして下さい。

- [yomu1_2019](https://github.com/TakosukeGH/yomu1_2019)

右上に「Fork」と書かれたボタンがあるので、それを押すだけでコピー完了です。

これで自分のGithubアカウントに読ム-1のサイトデータがコピーされましたので、
とりあえずこれを公開してみましょう。

以下のサイトを参考にnetlifyアカウントを作成：サイトを公開して下さい。

- [高機能ホスティングサービスNetlifyについて調べて使ってみた](https://qiita.com/sugo/items/2ee64887d682b0dae635)

リポジトリは、さっきコピーしてきたGithubのyomu1リポジトリを選択して下さい。
他の設定は以下の通りです。

- Build command: hugo
- Publish directory: public

設定からサイト名を変更できます。
あとで「yomu1-2019」など分かりやすいものに変更して下さい。

これでサイトの公開が完了です。続いて編集の手順を説明します。

Github上でファイルの編集が可能ですが、
自分のPCにファイルをコピーして編集することが可能です。

ここでは簡単にコピーできるGithub Desktopを紹介します。

- [GitHub Desktop v1.0.0 リリース ＆ さっそく使う](https://azriton.github.io/2017/09/23/GitHub-Desktop-v1.0.0リリース＆さっそく使う/)

自分のPCにファイルをコピーしたら、好きなエディタで編集して下さい。


GitHub Desktopもインストーラーが用意されているので、
↓からダウンロード・インストールして下さい。
<https://desktop.github.com/>

Hugoについてですが、これは静的サイトジェネレータと言われるもので、
テキストファイルをもとに、サイト構築に必要なHTMLファイル等を生成するツールです。

ダウンロードはいくつか方法があるのですが、
分かりやすいのはzipをダウンロードする方法です。

↓のサイトなどを参考にダウンロード・設定を行って下さい。
<https://www.imuza.com/entry/2018/02/09/164628>
<https://knooto.info/hugo/>

※Hugo公式サイトでは各種パッケージマネージャを使用したインストール方法が案内されてますので、
パッケージマネージャ使用する方は↓の内容を確認して下さい。
<https://gohugo.io/getting-started/installing/>




