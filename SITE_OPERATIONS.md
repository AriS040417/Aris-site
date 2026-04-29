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

## Brand Tone Guardrails (AriS)

- 売り込み感の強い文言は使わない（例: 今すぐ登録、急いで、最安など）
- トーンは「素朴・誠実・静かな熱量」を優先する
- CTAは最大2つまで。命令口調ではなく案内口調にする
- 実績の誇張はしない。事実ベースで短く書く
- 余白と読みやすさを優先し、情報を詰め込みすぎない

## Research Baseline (Simple Artist Sites)

下記は「売り込み感が薄い/素朴」方向の参考先として継続参照する。

- 米津玄師 official site: http://reissuerecords.net/
- 田中沁 Official Website: https://shintanaka.com/
- 三枝聡 Official Website: https://satoshisaegusa.com/
- 高橋遥平 Official Website: https://www.yt-drums.com/
- ミムラシンゴ website: http://shingo-mimura.com/

## Ongoing Research Policy

- 変更提案前に、上記参考サイトの導線・文体・情報量を簡易比較する
- AriSサイトへの提案は「控えめ」「読みやすい」「押し売りしない」を満たす案のみ採用する
- 強い販促ワードが入る場合は自動で弱める（案内口調に置換）
- 新しい参考サイトが見つかればこのファイルに追加して更新履歴を残す
