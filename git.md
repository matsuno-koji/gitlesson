# git の用語

1. ブランチ
   本体とは別のルートで作業するスペースのこと
   ブランチを切る=作業スペースを作成する
1. コミット
   作業内容を保存する行為のこと

1. ステージング
   保存する作業内容を指定すること

1. マージ
   作業したブランチの内容を追加したいブランチに反映させる

## 基本的なフロー

- ブランチで作業をします。
- コミットする内容をステージングします。
- ステージングした内容をコミットします。
- 作業内容を master ブランチにマージする。

## リモートリポジトリへの接続について

### **_https 接続_**

https 接続ってなに？
あんまり強いセキュリティじゃないけどそこそこ強い通信方式

### **_SSH 接続_**

強いセキュリティの接続
秘密鍵と公開鍵
github 側が秘密鍵を持ってる
俺のパソコンが公開鍵を持ってる

公開鍵を作ります
公開鍵を github に登録します
ssh 接続を試みます
