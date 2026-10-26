# ムダギリ診断｜第3章・未来攻略クエスト（再設計試作）

現在公開しているのは**完成版ではなく、質問・リザルトを検証する独立試作**です。

## 直接試す

- **[第1章→第2章→第3章を続けて試す](https://mudagiri.github.io/pilot/chapter2-v32/pilot/money-type/?chapter3v2=1)**（架空データのみ）
- **[第3章だけを直接遊ぶ（4問→リザルト）](https://mudagiri.github.io/?chapter3solo=1)**
- **[第3章リザルトのサンプルを見る](https://mudagiri.github.io/?chapter3solo=1)**（開始画面から1タップ）
- [プレビュー案内](https://mudagiri.github.io/chapter3-v2-preview.html)

単独試作の4場面：「叶えたい未来」→「今の障害」→「守りたいもの」→「今週使える手段」。結果には攻略ルート、理由、最初の一手、**この場で選べる「自分で進む／作戦を相談する」2つの道**、本人が選んだ条件を表示します。固定の7・30・90日ロードマップは削除しました。**第1章JOB・第2章の実際の家計データは、この単独試作では未連携。** 家計診断本体や従来の本番Pagesは変更していません。

## デプロイとQA

- [公開GitHub Actions](./.github/workflows/deploy.yml)：独立Pagesのみ
- ソース：[PR #77](https://github.com/mudagiri/mudagii/pull/77) の検証済み `953c174d85df7f9d5ebcc5772b40b608d0fba391`（固定）
- [Chromium・WebKitでの操作テスト成功](https://github.com/mudagiri/mudagii/actions/runs/39962788688)
- [独立GitHub Pages公開・背景画像の実URLテスト成功](https://github.com/mudagiri/mudagiri.github.io/actions/runs/40374545395)

**未完了**：実ユーザーへのインタビューと4視点100点監査、実スマホのデザイン確認、正式本番へのC1/C2/C3取り込み、本当の面談予約、専用素材。本番の第1章GAS接続先は別途要設定。独立プレビュー内のC1/C2→C3連携は動作確認済み。「数値の改善額」「投資適合性」「必ず稼げる」は表示しません。

公開版はGAS/分析への外部送信を無効にした確認用。個人の実情報は入力せず、架空の条件で確認してください。
