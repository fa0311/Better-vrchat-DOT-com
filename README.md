# Better vrchat DOT com
VRChat公式サイトをちょっと便利にするChrome向け拡張機能

## VRChat APIは公式にはサポートされておりません、そのため当拡張機能が利用できなくなったり、予想外の動作をするようになったり、ログインしているアカウントがBANされるなどの可能性が存在します。完全に自己責任でご使用ください
当拡張機能は [MITライセンス](https://github.com/riku1227/VRChatPlus/blob/master/LICENSE) で配布されています

## [ダウンロード(Chrome ウェブストア)](https://chrome.google.com/webstore/detail/vrchat%2B/joaffhoebddkohkafembmdkfmmcgmepj)

## 機能一覧
* フレンドがいるインスタンスにいるユーザー数を表示
  * 更新ボタンを押すことでそのインスタンスのユーザー数情報を更新することができます

## 安全性について
当拡張機能はID / パスワードの入力は必要ありません。  
VRChat APIを使用するため、Cookieに保存されているトークン(認証情報)をVRChatのサーバーに送信します。  
拡張機能自体は ID / パスワード / トークン などの認証情報を一切取得しておりません。  


## 更新履歴 
### 2.0.0
* 最新(2022/09/11現在)のウェブサイトに対応
* FAPシステムの機能を削除しました
* 公式に追加されたのでお気に入りアバターを表示する機能を削除
* アバターIDからお気に入り登録する機能を削除
  * 再実装する可能性はあり
* アバターをセットする機能を削除
  * 再実装する可能性はあり
### v1.3.0
* 拡張機能の名前を "VRChat+" から "Better vrchat DOT com" に変更
* Favorite Avatar Preset Systemの機能を削除/変更 
* お気に入りアバターをアバターIDから追加する時のエラーメッセージが正しく表示されるように
* アバターのお気に入りを解除するときのダイアログにそのアバターの名前を表示するように
### v1.2.0
* Favorite Avatar Preset Systemを追加
### v1.1.0
* INVITE MEボタンを追加
* インスタンスにいるユーザー数を更新するボタンを追加 
### v1.0.1
* ログを削除
### v1.0.0
* 初回リリース