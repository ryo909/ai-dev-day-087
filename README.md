# Day087 — 返信約束抜け棚

> メールやチャットで約束した返答・添付・確認事項を、終業前に棚卸しするツールです。
>
> Complexity Tier: medium
>
> Selected Components: none
>
> Family / Mechanic: message_promise_followup / status_shelf
>
> Input -> Output: message_rows -> action_shelf
>
> Audience Promise: 終業前に抜けている約束だけを拾える。

## 使い方

このツールでできること
メールやチャットで約束した返答・添付・確認事項を、終業前に棚卸しするツールです。

こんな時に使います
終業前、今日返すと約束したものが抜けていないか確認する時に使います。

使い方
1. 項目を入れる
2. 追加や編集をする
3. 結果を見る

## Story

- [制作ストーリー](./STORY.md)
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.
- Publish hook: 相手、約束した物、期限、元メッセージの一文を入れると、返答済み・添付待ち・確認待ちが棚で分かれる。

## Demo

🌐 [GitHub Pages](https://ryo909.github.io/ai-dev-day-087/)

---

Day087 / #100日開発
