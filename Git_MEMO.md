# Git 基本の用語集

|用語 |意味！
|--|--
|リポジトリ|履歴管理を行う場所。
|リモートリポジトリ|サーバーにあるリポジトリ。基本はベアリポジトリで運用される
|ローカルリポジトリ |自分のPCにあるリポジトリ。基本はノンベアリポジトリで運用される。
|ベアリポジトリ|ワークツリーを持たず、チェックアウト、マージができないリポジトリ。
|ノンベアリポジトリ|ワークツリーを持ち、チェックアウト、マージができるリポジトリ。
|ワークツリー |履歴管理を行いたいファイルがある場所。
|インデックス |コミットしたいファイル又はファイルの一部を登録するところ。
|ステージ |ワークツリーからコミットしたいファイル又はファイルの一部をIndexに登録すること。
|ハンク |変更した一範囲。
|コミット |インデックスに登録してある変更対象をローカルリポジトリに反映すること。
|リセット |コミット前の変更をローカルリポジトリの状態へ戻すこと。また、特定のコミットまで状態を戻すこと。ただし、ローカルリポジトリに限られる。
|ヘッド |作業対象となっているブランチ、コミット。
|チェックアウト |ヘッドを切り替えること。過去のコミットを対象にチェックアウトした場合、それをもとにコミットすることはできない。
|プッシュ |ローカルリポジトリの変更をリモートリポジトリに反映させること。
|プル |リモートリポジトリの変更をローカルリポジトリに反映させること。フェッチ＋マージ
|フェッチ |リモートリポジトリの変更をローカルリポジトリに反映させること。フェッチ＋マージ
|マージ |異なるブランチの変更を反映させること。お互いの変更履歴が残る。
|リベース |異なるブランチの変更を反映させること。変更履歴が片方に集約される。
|コンフリクト |マージ対象の２ファイルで同じ箇所が変更されており、自動でマージができないこと。
|ブランチ |履歴管理を枝分かれさせてたもの。ブランチを使うこちにより、複数の履歴を並列に管理できる。
|フォーク |リモートリポジトリをコピーしてリモートリポジトリを作成すること。
|クローン |リモートリポジトリをコピーしてローカルリポジトリを作成すること。
|プルリクエスト |フォークしたリポジトリでの変更を、フォーク元のリポジトリへ反映するよう依頼すること。
|.gitignore |履歴管理の対象外とするファイルを登録するところ。対象範囲は各リポジトリ。
|.gitignore (グローバル) |履歴管理の対象外とするファイルを登録するところ。対象範囲は全リポジトリ。

[C:\Users\Public\共有\01.NIC](C:\Users\Public\共有\01.NIC)
