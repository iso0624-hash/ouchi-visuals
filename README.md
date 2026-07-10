# ouchi visuals

`ouchi-content-drafts/user_up/photo` のフォルダ階層から生成する、画像専用のGitHub Pagesサイトです。

- 文章サイト `ouchi-texts` とは完全に分離しています。
- フォルダはカテゴリまたはアルバム、画像は展示物として扱います。
- `未分類`、`_inbox`、`_sorted`、空フォルダは公開しません。
- 画像を追加・更新する場合は、生成器の dry-run で予定を確認してから本番実行します。
- 本番生成後に `publish.bat "Update visual gallery"` でGitHubへ反映します。
