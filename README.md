# TableSnap Pro — Landing Page

TableSnap Pro v2.0 の公式ランディングページ（静的 HTML）。

## 内容

- Excel (TSV) / Markdown 出力の訴求
- 4 つの抽出モード、端末内処理、Obsidian / AI 向けユースケース
- デモ用サンプル表（拡張機能の動作確認用）
- 日英切り替え（JP / EN）
- Chrome Web Store / note マガジン / GitHub へのリンク

## ローカル確認

```bash
# 任意の静的サーバーで
python3 -m http.server 8080
# http://localhost:8080 を開く
```

または `index.html` をブラウザで直接開いても確認できます。

## Vercel デプロイ

1. GitHub に `tablesnap-pro-lp` リポジトリを作成して push
2. [Vercel](https://vercel.com) → **Add New Project** → リポジトリを選択
3. Framework Preset: **Other**（ビルドコマンド不要）
4. Deploy

Root Directory に `index.html` があるため、そのまま公開されます。

## リンク

- Chrome Web Store: https://chromewebstore.google.com/detail/tablesnap-pro/lhkdcojfnpencjimnbkhbigkjbnpdjdg
- note v2.0 記事: https://note.com/ktech_dev/n/n969b2f51ffe4
- note マガジン: https://note.com/ktech_dev/m/mfb632f0481c2
- 拡張機能リポジトリ: https://github.com/crossbeat461-a11y/tablesnap-pro
- K-Tech Studio: https://k-tech-lab.vercel.app/
- Buy Me a Coffee: https://buymeacoffee.com/k_tech_studio

## ファイル構成

```
tablesnap-pro-lp/
├── index.html
├── favicon.png
├── images/icon128.png
├── .gitattributes
└── README.md
```

スクリーンショットを追加する場合は `images/` に配置し、`index.html` の UI モック部分を `<img>` に差し替えてください。
