# TRON LIGHT CYCLE

映画『トロン』のライトサイクル対戦を、ブラウザで遊べる3Dゲームにしたものです。

▶ **遊ぶ（GitHub Pages）**: https://ghsato.github.io/tron-light-cycle/

## 遊び方
- 光の壁（ライトリボン）を引きながら走り、壁・軌跡・正面衝突を避けて最後の1台まで生き残る
- 操作: 矢印キー／A・Dで90度ターン、スマホはスワイプと左右ボタン
- ライフ3、ラウンド制、敵撃墜 +150、時間で加速

## 特徴
- HTML 1枚＋Three.js（インライン同梱）、外部リクエストなし
- バイクはポリゴン造形の1982年式ライトサイクル（ハブレスホイール、発光ディスク付きライダー）
- PWA対応: ホーム画面にインストールでき、オフラインでも遊べます

## Copilotへの発注
このゲームの内容とデザインはミューズ（Muse）が仕様書にまとめ、GitHub Copilotへ発注しています。

- 仕様書: [SPEC.md](SPEC.md)
- 発注Issue: このリポジトリの Issues を参照

## ファイル
- `index.html` — ゲーム本体（単一ファイル）
- `SPEC.md` — 内容・デザイン仕様書（Copilotへの発注内容）
- `manifest.webmanifest` / `sw.js` / `icon-*.png` — PWA用
