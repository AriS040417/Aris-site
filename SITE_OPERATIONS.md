# AriS Site Operations

このファイルは、公式サイト運用時に毎回参照する固定情報です。
今後の更新ではこの内容を基準にします。

## Official

- Site repository: https://github.com/AriS040417/Aris-site
- Site page URL: https://aris040417.github.io/Aris-site/

## SNS / Music Links

- YouTube channel: http://youtube.com/channel/UCkBIv56CIs7rqstj8mDWkJQ
- Instagram: https://www.instagram.com/aris_20040417
- TikTok: http://tiktok.com/@aris040417
- X: http://x.com/higher26656657
- TuneCore: https://www.tunecore.co.jp/artists/AriS
- TwitCasting: https://twitcasting.tv/

## Current Automation Settings

- `AUTO_LYRIC_UPDATE = true`
- `YOUTUBE_CHANNEL_ID = UCkBIv56CIs7rqstj8mDWkJQ`
- `LATEST_YOUTUBE_URL = https://youtu.be/GUQmNnjgEE0` (fallback)

## Rule For Latest Song Auto Switch

- 新規投稿のうち、タイトルに `Lyric` を含む動画を優先して採用する
- `Shorts` は自動切替対象から除外する
- 自動取得失敗時は `LATEST_YOUTUBE_URL` にフォールバックする
