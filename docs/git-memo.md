---
layout: page
title: "git memo"
permalink: /docs/git-memo
---

# ソフトウェア工学 2024

講義で学んだことをmarkdown形式でまとめる。

## git
gitとは分散管理型のバージョン管理システムのことであり、以下のような特徴を持つ．  
元々はオープンソースソフトウェア管理のためのソフトウェア  
変更履歴が残る  
変更した箇所に戻ることができる  
他人と共同編集できる  

コミット  
[ファイル作成／変更／削除]の記録  
いつ・誰が・なにを・どのような  
コミットにメッセージを残す（「どのような」を記載）   
対象ファイルは一つでも複数でもよい  
コミットの単位はユーザーが自由に決定する  

レポジトリ  
gitが管理するプロジェクトのフォルダ  
ローカルレポジトリ  
個々のプロジェクト実行環境  
リモートレポジトリ  
共有の管理場所  
Github/Gitlab など  

ワークツリー（worktree）  
gitでのファイルの管理状態を表す  
untracked  
gitで管理されていないファイルの状態  
unmodified  
gitで管理されているが変更されていないファイルの状態  
modified  
gitで管理されていて変更されたファイルの状態  

### 主なコマンド
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
