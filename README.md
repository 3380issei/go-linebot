# 【Go+ngrok】オウム返し LINEbot

## 使い方

1. [LINE Developers](https://developers.line.biz/ja/)にログイン
2. チャネルを作成
3. チャネルアクセストークンとチャネルシークレットをコピぺ
4. `$ go run main.go`でローカルに API サーバーを起動
5. `$ brew install ngrok`で ngrok をインストール
6. `$ ngrok http 8080`で localhost8080 を公開
7. ngrok のターミナルに表示された URL+/callback を LINEbot の webhookURL にコピペ
