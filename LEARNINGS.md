# LEARNINGS — 328 STEALTH ORBIT

## 2026-10-21 公開

- 十字パッド、A/B/C、音、USB コントローラーは既存。操作帯は作り直していない。
- 公開入口が `stealth-orbit5.html` だけだったので `index.html` を置き、旧名は転送にした。
- 拡大防止（viewport、`touch-action: none`、300ms の `touchend`、`dblclick`、`gesture*`）と、プレイ中の一時停止、`tg.328.mute` を追加。
- Three.js r128 は CDN をやめ、同梱した。
- フォルダは `328-stealth-orbit`。旧 URL は公開前に 404。
- ハーネス PASS: `docs/harness-reports/328-stealth-orbit-2026-10-21T11-20-56-562Z.md`（48 RAF/秒、0.65MB、エラー0）。
- 未検証: iPhone 実機の操作感と音。
