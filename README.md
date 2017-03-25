# Gitの勉強
- git add コマンドで、リポジトリに変更情報を追加する
    - このことをステージングと言う
- git commit コマンドで、リポジトリのインデックスに追加された変更情報にコメントを付けてコミットできる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる

- git config --global alias.co "commit" で，commitをcoと省略した．
- https://${あなたのusername}.github.io/git-study/などでgh-pagesのWebサイトが見れるぞ！

- ブランチ
    - master:常にリリース可能な状態にしておく
    - develop:ここで開発を行っていく
    - feature:新規機能，バグ修正．developからcommitしてdevelopにmerge
    - release:リリースを行う準備，最終確認
    - hotfix:緊急の修正のブランチ，masterに直接merge