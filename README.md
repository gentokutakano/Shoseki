# アプリケーションの概要
読んだ書籍を記録して共有できる、おすすめ書籍投稿サービス。

# 技術的ポイント
・herokuを用いたRails本番環境構築(https://shoseki-app.herokuapp.com/)
・Dockerを用いたRails開発環境構築
・CircleCIによる自動ビルド＆テスト
・Gitによる自動デプロイ
・RSpecでテスト記述
・Ajaxを用いた非同期処理（お気に入り登録/未登録などの切り替え表示）
・Bulmaによるレスポンシブ対応
・Rubocopを使用したコード規約に沿った開発

# アプリケーションの機能
・読んだ書籍を投稿
・画像を正方形に整形して投稿（refileを使用）
・別ユーザーの書籍に対して「いいね!」機能
・ログイン
・ログイン状態の保持
・ゲストユーザーログイン
・モデルに対するバリデーション

# 環境
■フレームワーク
　Ruby on Rails
■インフラ
　AWS s3, Docker
■データベース
　MySQL