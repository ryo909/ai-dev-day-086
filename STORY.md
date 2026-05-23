# Day086 Story — Laundry Escape Window Compass

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day086専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: laundry_weather_window
- Mechanic: window_adjust
- Input/Output: editable_rows -> time_window_cards
- Audience Promise: 出発前に外干し継続か部屋干し切替かを決められる。
- Publish Hook: 洗濯物の量、帰宅時刻、雨の不安、部屋干し余白を入れると、外干しで逃げ切れる窓と切替時刻が一本で見える。
- Complexity Tier: small
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
Day086｜洗濯逃げ窓コンパス
外出前に、洗濯物を外干しで逃げ切れるか部屋干しへ切り替えるか決めるツールです。
