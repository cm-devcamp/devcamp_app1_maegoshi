Devcamp Products Webサイト
=========================

当Webサイトのリポジトリです。 `docs/` がドキュメントルートで、HTMLファイルや画像ファイルを配置します。

![workflow](https://github.com/cm-devcamp/devcamp_app1_prod/actions/workflows/super-linter.yml/badge.svg)

## リポジトリ運用ルール

mainブランチへの直接のコミットは控えてください。作業用ブランチを作成し、Pull Requestでレビューののちmainにマージします。

## docs/index.html の説明

トップページの構造は以下です。各項目は `index.html` 内にコメント `<!-- 項目名 -->` で箇所を記載しています。

- ナビゲーションメニュー
  - Products: 商品一覧ページへのリンク。商品一覧ページは開発中です
  - About us: 会社概要ページへのリンク。会社概要ページは開発中です
  - Contact: トップページ下方のアンカー `#contact` へのリンク。問い合わせフォームを追加予定です
- H1: Webサイトのキャッチフレーズ
- News: 新着情報
- X/Twitter: X/Twitterのつぶやきを埋め込み予定です。幅480px、高さ270px
- Youtube: Youtube動画を埋め込み予定です。幅480px、高さ270px
- Contact: 問い合わせフォームを追加予定です。

## ライブラリなどのライセンス利用について

商用ライセンスやOSSのライブラリ、画像などを利用する場合は各ライセンス規定を遵守してください。表記既定のあるものは、HTMLファイルや他のファイルに含めて構いません。