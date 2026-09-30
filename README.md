# bracket-print

A4の手書き用トーナメント表。4・8・16・32枠、縦横切り替えに対応。

## 初回公開

1. この一式をリポジトリのルートに配置します。
   `index.html` と `.github/workflows/pages.yml` の両方が必要です。
2. GitHubの Settings → Pages → Build and deployment → Source で
   **GitHub Actions** を選択します。
3. Actions → Deploy to GitHub Pages → Run workflow で初回公開できます。

## 更新

差分ZIPは解凍し、変更ファイルを同じパスへ上書きして、既定ブランチ
（main または master）へコミットしてください。自動で公開されます。
ZIPファイルそのもののアップロードでは内容は展開されません。

## PDF出力

枠数と縦横を選び、「PDF出力」を押します。印刷画面でPDF保存を選び、
用紙A4、倍率100%、ヘッダーとフッターをオフにしてください。

## ファイル

- `index.html`: ツール本体
- `.github/workflows/pages.yml`: 自動公開の設定

ActionsはNode.js 24に対応したバージョンを使用しています。
