# family-backend

## インフラ
* 画像保存: S3
* 認証認可: Cognito User Pool (認証用)、Cognito Identity Pool (API gatewayとS3へのアクセス用のトークン発行用)
* バックエンドロジック: Lambda (express)
* フレームワーク: Serverless Framework
