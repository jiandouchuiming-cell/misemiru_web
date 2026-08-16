# misemeiru_web

ミセミルWebのWebサイト本体を管理するリポジトリです。このREADMEは、コードとGit設定から確認できる技術情報を記録します。契約・承認・公開等の業務状態は推測せず、未確認項目を `要確認` としています。

## 1. 基本情報・現在の状態

- 案件名: misemeiru_web
- 内容: ミセミルWebのサービス案内を含む静的Webサイト
- 現在の制作・承認・公開・保守状態: 要確認
- 正式な公開URL: 要確認
- README最終更新日: 2026-08-16

## 2. Repository

- GitHub: https://github.com/jiandouchuiming-cell/misemiru_web.git
- 基準branch: `main`
- 公開済み安定版を示すcommit / tag: 要確認

## 3. 技術構成

- HTML / CSS / JavaScript
- JavaScriptは `index.html` 内に記述
- package manager: なし
- `package.json`: なし
- Node.js指定: なし
- 専用build工程: なし

## 4. セットアップ・確認方法

依存関係のインストールは不要です。専用の開発起動コマンドはありません。ルートの `index.html` と関連アセットを静的サイトとして確認します。

### Build

- buildコマンド: なし
- build出力先: なし

存在しないnpmコマンドを追加・実行しないでください。

## 5. 主な構成と更新箇所

- `index.html`: サイト本文、サービス情報、主要リンク、SEO情報、JavaScript
- `assets/`: サイトで利用する画像等
- `misemiru_web_split_transparent_assets/icons/`: アイコン素材
- `misemiru_web_split_transparent_assets/photos/`: 写真素材

店舗・サービス情報を変更するときは `index.html` 内の重複表記を検索し、確認済み情報だけを反映します。画像差し替え時は参照パス、表示サイズ、代替テキストも確認します。

## 6. 外部サービス・フォーム

- Googleフォームへの外部リンク
- Instagramへの外部リンク
- Google Fonts
- リポジトリ内で送信処理を持つフォーム: なし
- Search Console設定: 要確認
- GA4等の計測タグ: コード上では確認できない

プライバシー文面にはアクセス解析を利用する場合がある旨の記載がありますが、実際の導入・運用状況は要確認です。外部URLやフォーム送信先を推測で変更しないでください。

## 7. SEO・リンク

- `title`、description、canonical、OGPは主に `index.html` で管理
- コード内のcanonical / OGP URL: `https://jiandouchuiming-cell.github.io/misemiru_web/`
- 上記URLが現在の正式な公開URLか: 要確認
- `href="#"` の導線とTODOコメントが残っているため、公開判断前に遷移先を確認する

## 8. 公開・ホスティング・ドメイン

- デプロイ設定ファイル: 確認できない
- ホスティング先: 要確認
- 独自ドメイン: 要確認
- DNS管理先・所有者: 要確認
- 公開手順: 要確認

コード内URLだけを根拠に、現在公開中またはGitHub Pages運用中とは判断しません。

## 9. QA・素材・引継ぎ

- リポジトリ内の公開前QAチェックリスト: 確認できない
- 画像・文章の利用許諾範囲: 要確認
- 公開前の確認者・承認条件: 要確認
- 復元はGit履歴を基準にし、安定版commit / tagは関係者へ確認する

共通QAテンプレートはリポジトリへ自動コピーせず、必要時に別途適用します。

## 10. 未確認事項

- 現在の案件状態、公開状態、承認状態、保守範囲
- 正式な公開URL、ホスティング、独自ドメイン、DNS
- GoogleフォームとInstagramの正式な運用先
- Search Console / GA4の導入・管理状況
- `href="#"` とTODO箇所の正式な遷移先・扱い
- 素材の権利確認状況、公開前QAと承認記録

## 11. 認証情報

パスワード、APIキー、秘密トークン、個人情報をREADMEやGitへ保存しないでください。必要な認証情報の保管先と共有方法は、関係者へ確認してください。
