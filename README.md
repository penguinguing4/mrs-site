# Misty Rose Studio - 公式サイト（最小構成）

静的な1ページサイトです。**GitHub Pages / Cloudflare Pages / Netlify / Vercel** いずれにもそのままデプロイできます。

## 使い方（GitHub Pages）
1. GitHubで新規リポを作成（例: `mrs-site`）。
2. このフォルダの中身をアップロード（`index.html`, `privacy.html`, `styles.css`）。
3. リポの **Settings → Pages** で
   - Source: `Deploy from a branch`
   - Branch: `main` / `/root` を指定
4. カスタムドメインを使う場合は、DNSに `CNAME` を追加し、Pages設定にドメインを入力。詳しくは公式: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## 使い方（Cloudflare Pages）
1. Cloudflare にログイン → **Workers & Pages → Create**。
2. GitHubリポを接続 or **Direct Upload** で本フォルダをアップロード。
3. Custom domains で独自ドメインを紐づけ。ドキュメント: https://developers.cloudflare.com/pages/configuration/custom-domains/

## 使い方（Netlify）
1. Netlifyにログインして **Add new site → Import an existing project**。
2. GitHubリポを接続（またはDrag & Dropで`index.html`をドロップ）。
3. カスタムドメインを設定。

## 編集ポイント
- `index.html`: テキスト、リンク、住所等を編集
- `privacy.html`: 各アプリのポリシーを追記
- `styles.css`: 色やフォント調整

## ライセンス
社内利用向けテンプレート。再配布はご相談ください。