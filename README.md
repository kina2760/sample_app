#sample_app

http://ec2-54-248-96-222.ap-northeast-1.compute.amazonaws.com/

#Twitter風SNS
主な機能
CRUD、パスワードリセット、画像投稿、いいね、フォロー、非同期画面遷移、メール認証、ページネーション、セキュリティ、投稿検索、ユーザー検索

#開発言語
Ruby(3.1.2),Ruby on Rails(7.0.4),HTML,CSS(bootstrap),Javascript.git

#ローカル開発環境
cloud9(AWS クラウドIDE)
データベース　sqlite3
Web,アプリケーションサーバー　puma

#本番環境
サーバー　Render→AWS (EC2)OS AmazonLinux2
データベース　PostgreSQL14?(Render)→Postgresql13
Webサーバー　nginx
アプリケーションサーバー　unicorn 3.6.2
javascript実行環境　Node.jp,yarn
ストレージ　S3(AWS)
メール送信　Mailgun

テストテストテスト
