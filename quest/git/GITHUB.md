# GitHub を使って開発を進めることができる

## 1. リモートリポジトリ

GitHub 上に新規リポジトリを作成してください。
→OK！

## 2. プッシュ

ローカルの PC 上に GitHub 上で作成したリポジトリの同じ名前のディレクトリを作成し、そのディレクトリ内に README.md　ファイルを作成してください。
→mkdir → touch

次に、ローカルリポジトリを新規作成し、変更をステージに追加、コミットしてください。
→git init → git add → git commit -m "最初のコミとです。"

リモートリポジトリを登録してください。そして GitHub に変更をプッシュしてください。
→git remote add リモート名 リモートリポジトリgithub URL → git push リモート名 ブランチ名

## 3. 追加の変更をプッシュ

README.md に変更を追加してください。そしてその変更を GitHub にプッシュしてください。
→変更 → git add → git commit → git push


## 4. クローン

GitHub 上にある他者が作成したリポジトリを自分の PC 上にクローンしてください。クローン対象は何でも良いです。
→git clone github_URL
