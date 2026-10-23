# ムダギリ診断｜第3章・未来攻略クエスト（再設計試作）

現在公開しているのは**完成版ではなく、質問・リザルトを検証する独立試作**です。

## 直接試す

- **[第3章だけを直接遊ぶ（4問→リザルト）](https://mudagiri.github.io/?chapter3solo=1)**
- **[第3章リザルトのサンプルを見る](https://mudagiri.github.io/?chapter3solo=1)**（開始画面から1タップ）
- [プレビュー案内](https://mudagiri.github.io/chapter3-v2-preview.html)

単独試作の4場面：「叶えたい未来」→「今の障害」→「守りたいもの」→「今週使える手段」。結果には攻略ルート、理由、最初の一手、7・30・90日の確認計画、本人が選んだ条件を表示します。**第1章JOB・第2章の実際の家計データは、この単独試作では未連携。** 家計診断本体や従来の本番Pagesは変更していません。

## デプロイとQA

- [公開GitHub Actions](./.github/workflows/deploy.yml)：独立Pagesのみ
- ソース：[PR #77](https://github.com/mudagiri/mudagii/pull/77) の検証済み `011aa65ec4f621eac3202e348eab0834e59f5459`（固定）
- [Chromium・WebKitでの操作テスト成功](https://github.com/mudagiri/mudagii/actions/runs/39890663464)
- [GitHub Pages本番URLスモークテスト成功](https://github.com/mudagiri/mudagiri.github.io/actions/runs/39890794565)

**未完了**：実ユーザーへのインタビューと4視点100点監査、正式C1/C2引継ぎ、本当の面談予約、専用素材・スマホ実機のデザイン確認。「数値の改善額」「投資適合性」「必ず稼げる」は表示しません。

公開版はGAS/分析への外部送信を無効にした確認用。個人の実情報は入力せず、架空の条件で確認してください。
