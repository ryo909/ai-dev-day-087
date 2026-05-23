# Day087 Story — Reply Promise Shelf

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day087専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: message_promise_followup
- Mechanic: status_shelf
- Input/Output: message_rows -> action_shelf
- Audience Promise: 終業前に抜けている約束だけを拾える。
- Publish Hook: 相手、約束した物、期限、元メッセージの一文を入れると、返答済み・添付待ち・確認待ちが棚で分かれる。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day087｜返信約束抜け棚
メールやチャットで約束した返答・添付・確認事項を、終業前に棚卸しするツールです。
