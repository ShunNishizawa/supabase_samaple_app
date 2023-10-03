# supabase_sample_app

## supabaseとは？

- Firebaseに変わるオープンソースBaaS
- FirebaseがNoSQLなのに対して、supabaseはPostgreSQLを採用
  - つまりRDBとなっている
- もちろん、認証機能、ストレージ機能、リアルタイム更新可能
- SQLやっていた人にとってはいいかもしれない

## 必要ライブラリ

`flutter pub add supabase_flutter`

`flutter pub add flutter_dotenv`
- こちらは必須ではないが、APIキーやsupabaseへのアクセスURLを公開しないようにするために、入れておく

## 使い方
- サンプルアプリのコード参照
