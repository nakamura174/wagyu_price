# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？  

 - リモートリポジトリ
    - ネット上に配置し複数人で共有するためのリポジトリ  
  
- ローカルリポジトリ
  - 開発者一人ひとりが使用するために自身のPC上に配置するためのリポジトリ  


## プッシュとマージの違いは何でしょうか？  

- プッシュ  
  - ローカルリポジトリで変更した内容をリモートリポジトリへ反映させること  
  
- マージ  
  - 各ブランチでの変更内容を別のブランチへ取り込むこと  
  

## コミットとプッシュの違い  
  - コミットとはステージング状態のデータをセーブデータのように変更履歴として残すためのもの。履歴を残す際にコミットメッセージという編集内容を示すメッセージを残すことができる。あくまでローカルリポジトリ内での記録。  
 プッシュとはローカルリポジトリでの編集内容をリモートリポジトリへ反映させること。  
  

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？  

  - 変更者以外が見た際もどのような変更を加えたのか分かり易いコメントを心がける。  

  - プレフィックス
    - 接頭辞としてコメントの頭にどんな事をしたのか簡潔に英語の動詞で表すこと(日本語でも可)
  
  - プレフィックスの例
    - Add: 追加
    - Fix: 修正
    - Improve: 改善
    - Update: 更新
    - Remove: 削除
    - Rename: (ファイル名の)変更
    - Move: 移動
    - Change: 変更
  

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？  

  - ローカルでマージする際は、変更した内容がコードレビューなしですぐに取り込まれる。  
 プルリクエストでマージする際は、取り込むまでに承認が必要な為、マージする内容が問題ないかどうか確認後に取り込むことが可能。
  


## コンフリクトを起こしてしまった場合、どう対処すべきですか？  

  1.  先にマージされた変更内容を取り込む  
  1.  後にマージしようとしている変更内容を取り込む  
  1.  どちらの変更内容も取り込む  