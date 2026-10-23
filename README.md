# ムダギリ診断｜第3章V2・独立プレビュー

このリポジトリは第3章V2の**隔離プレビュー**をGitHub Pagesで公開するためのものです。既存の第1章・第2章の本番 `mudagiri/mudagii` は上書きしません。

## プレビューを開く

- **[第3章V2プレビューの入口](https://mudagiri.github.io/chapter3-v2-preview.html)**
- [第1章から通して体験](https://mudagiri.github.io/pilot/chapter2-v32/pilot/money-type/)
- [第2章から体験](https://mudagiri.github.io/pilot/chapter2-v32/)

> **開発・確認用です。** 収入、実家計、氏名などの実データは入力せず、架空の数字で操作してください。隔離版はGAS/分析サービスへの送信・実LINE予約をしない設定でビルドしています。

## デプロイ方式

- GitHub Actions: [Chapter3 V2 Independent GitHub Pages Demo](./.github/workflows/deploy.yml)
- 参照元: [mudagiri/mudagii PR #77](https://github.com/mudagiri/mudagii/pull/77)
- **固定ソースコミット**: `a860bc8f40883dbdaff0259afce3d42df48dc4fe`（Chromium・WebKitの通しQA合格済み）
- [初回デプロイ成功ログ](https://github.com/mudagiri/mudagiri.github.io/actions/runs/39887562513)

作業用ブランチを更新しても、公開中のコードは自動で変わりません。新しいソースを公開したい場合は、QAを再実行してから`.github/workflows/deploy.yml`の`ref`を変更してください。

実スマホでのデザイン監査、4視点100点評価、ユーザーPilot、面談予約CVはまだ未完了です。
