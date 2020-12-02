# family-backend

## インフラ

- 画像保存: S3
- 認証認可: Cognito User Pool (認証用)、Cognito Identity Pool (API gateway と S3 へのアクセス用のトークン発行用)
- バックエンドロジック: Lambda (express)
- フレームワーク: Serverless Framework
- その他: typescript, clean architecture (inversify)
