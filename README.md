# MG的GitHub運用方針

* 共同開発者の追加はプロジェクトの管理者がCollaboratorsに追加。
* ブランチの構成は以下の通り
	```
	master
	 ->develop
	   ->feature/XXXXX
	   ->feature/YYYYY
	 ```
	- featureブランチは作業毎に作成。「feature/ログイン画面作成」とか
* 作業が完了したらdevelopブランチに対する Pull Request を投げる。
	- Pull Requestには Reviewrs に共同開発者(の内レビュアーになる人)を追加する。
* レビュアーはレビューして問題なければ Approve (承認) する。
	- NGならコメントをNGの理由をコメントする
* 全員の承認を得たら、develop ブランチにマージして feaure/・・・ブランチは削除する。
