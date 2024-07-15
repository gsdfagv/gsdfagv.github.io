以下にgitコマンドをまとめる．

git merge --abort 
main ブランチを、マージを試行する前の状態に復元
git pull コマンドを実行して、マージ先の変更を取得
新しいブランチを作成し、変更を行って、そのブランチを main ブランチにマージ
変更をプッシュ
git reset --hard
マージを開始する前の状態に戻す
影響を受けたファイルに Git によって挿入された情報を使用して、手動で解決
git init
gitの初期化・設定開始
git status
ワークツリーのステータスを表示
git config 
設定周りの確認・変更
git log
ログを表示
-- onelineでコミットメッセージの1行のみの一覧表示
git diff
ファイルの差分を表示
git add
ステージングエリアに追加
git commit 
コミットの実行
git commit --amend --no-edit
コミットの修正
git checkout
削除されたファイルを復旧や過去コミットの復元など（元に戻す変更がstaging area/index内にある場合）
git reset
コミットのリセット
git revert
「コミットの変更を打ち消す」コミット
git rm
ファイルとindex情報の削除
git clone
レポジトリをコピー
git pull
リモートレポジトリの同期	
git push
変更をアップロードする
git request-pull
プルリクエスト：変更依頼
git remote
リモートレポジトリの設定
git branch
ブランチの作成
git checkout
ブランチの切り替え
git merge
ブランチの統合
--ff-only: fast forward only. 変更のない統合先ブランチにマージ
git clone
レポジトリをコピー
git push
変更をアップロードする
