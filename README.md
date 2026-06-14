# （作成中）AIの研究、挑戦の歴史（1990年〜2026年）

プログラマー視点でまとめたAI通史（Webページ版）です。

ベースをCaludeに作成させ、内容を1つずつ確認しながら書き足しています。

## GitHub Pages で公開する手順

1. GitHubで新しいリポジトリを作成する。
2. この `index.html`（と任意で `README.md`）をリポジトリ直下に push する。
   ```bash
   git init
   git add index.html README.md
   git commit -m "AI history timeline page"
   git branch -M main
   git remote add origin https://github.com/<ユーザー名>/<リポジトリ名>.git
   git push -u origin main
   ```
1. [公開ページのURL](https://windhole.github.io/whc-ai-history/)

3. リポジトリの **Settings → Pages** を開く。
4. **Source** を `Deploy from a branch`、**Branch** を `main` / `/ (root)` に設定して Save。
5. 数十秒〜数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開される。

## 補足

- フォントは Google Fonts をCDNから読み込みます（オフライン環境では既定フォントにフォールバック）。
- 1ファイル完結なので、ビルド・ビルドツール・依存パッケージは不要です。
- `prefers-reduced-motion` とキーボードフォーカスに対応済み。スマホ表示も最適化済み。
