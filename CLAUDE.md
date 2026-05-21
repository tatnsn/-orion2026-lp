# ORiON制作委員会 ランディングページ

orion2026.jp の公式サイト（静的HTML）。

## 技術スタック
- 静的HTML / CSS / JavaScript（フレームワークなし）
- **Netlify** でホスティング（自動デプロイ）

## デプロイ
- GitHub: `https://github.com/tatnsn/-orion2026-lp`
- 本番URL: `https://orion2026.jp`
- `master` にプッシュ → GitHub Actions → Netlify 自動デプロイ

## ファイル構成
- `index.html` — メインページ（全コンテンツ）
- `orion-logo.png` — ロゴ画像
- `robots.txt` / `sitemap.xml` — SEO設定
- `netlify.toml` — Netlifyヘッダー設定

## コード変更後のデプロイ手順
```bash
git add <ファイル>
git commit -m "メッセージ"
git push origin master
# → GitHub Actions が自動でNetlifyにデプロイ（orion2026.jp に反映）
```
