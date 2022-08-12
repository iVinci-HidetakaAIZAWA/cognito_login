"# cognito_login" 

個人PCでvinciのgithubアカウント使う：OK
個人PCで個人のgithubアカウント使う：OKですが、社内で共有したいのでなるべくvinciアカウントでお願いしたいです。
あとセキュリティ的にロボのコードとかをvinciのリポジトリや他のリポジトリにコピペとかするのは絶対にNGです！基本vinciのリポジトリはprivateになっているのでそこは安心できるかなと思ってます！

ロボのコードを個人PCにクローンはNGですね！

- APIの認証
  1 Cognito
  2 Route53
- APIGateway
- Lambda
- DynamoDB
  1 python によるCRUD記述方法
  2 サービス運用していくためのDB設計
    a DynamoDBを使ったサービス例を収集する
    b DynamoDBのパフォーマンス
- インフラコード
  1 CloudFoundation
  2 CDK
  3 AWS sam
- ローカル開発環境構築
  1 vagrant
  2 AWS sam+APIGatewayのエミュレータ
  3 デバック実行ができる環境（vscode??）
  4 S3(minio)
