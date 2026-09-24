# note運用プロジェクト(水瀬@会社員×AI副業)

会社員×AI副業をテーマにしたnote有料記事の企画・執筆・運用チーム用リポジトリ。

## フォルダ構成

- `drafts/` — note記事の下書き(`draft_NN_スラッグ.md`形式、番号は投稿順)
- `assets/` — プロフィールアイコンなどの画像素材
- `.claude/agents/` — 運用チームの役割定義(編集長・市場リサーチ・記事企画・ライター等)
- `sales_tracking.md` — 公開後の実績記録(閲覧数・購入数・改善メモ)

## 記事一覧

| ファイル | タイトル | テーマ |
|---|---|---|
| [drafts/draft_01_ai_writing_side_job.md](drafts/draft_01_ai_writing_side_job.md) | ChatGPTで月3万円。会社員が土日だけで始めるAIライティング副業の教科書 | 受注〜納品の全体像 |
| [drafts/draft_02_x_growth_prompts.md](drafts/draft_02_x_growth_prompts.md) | ChatGPTで「バズる型」を量産する。会社員のためのX運用ノウハウnote | X(SNS)運用 |
| [drafts/draft_03_repeat_clients.md](drafts/draft_03_repeat_clients.md) | 「また、お願いします」を引き出す。副業ライター/SNS運用代行が"単発"を"継続案件"に変える教科書 | 継続案件化・紹介 |
| [drafts/draft_04_shortvideo_script_agency.md](drafts/draft_04_shortvideo_script_agency.md) | AIで台本を量産する。会社員が土日だけで始める「ショート動画運用代行」副業の教科書 | ショート動画(TikTok/リール)台本づくり代行 |
| [drafts/draft_05_review_reply_agency.md](drafts/draft_05_review_reply_agency.md) | ChatGPTで口コミ返信を代行する。会社員が土日だけで始める「レビュー返信代行」副業の教科書 | 店舗向け口コミ・レビュー返信代行 |

## 自動生成ルーティン

毎日9:00(日本時間)に、クラウド上で新しい下書きを1本自動生成するルーティンが動いています(市場リサーチ→企画→執筆→編集長レビュー→`drafts/`にコミット)。noteへの実際の投稿・SNS投稿・価格変更は行わないため、公開前に必ず人間の確認が必要です。
