## 問題
- アプリを離脱する人がいるのはいつだって嫌なものです。
- アプリから離脱した人に通知を送ってみましょう。

## 要件
1. アプリから離脱した人に対して、離脱時間から60秒後にローカル通知を表出。
2. 通知をタップするとトップ画面に着地する。 

## ヒント
- さらに難しくなります。(説明外のことがたくさん出てきます。)
- AlermManagerの利用が必要になります。
- BroadcastReceiverの利用や、それに伴うAndroidManifestの修正などが必要になります。

## 学び
- 他のActivity/Serviceの利用を学ぶ。
- 少しだけ深くAndroidManifestを理解する。

## 実際の案件
ローカル通知はネイティブアプリケーションの一つの肝です。特定の条件で発火させてユーザに戻ってきてもらいたいからです。
ローカル通知に関する案件もたくさん存在します。