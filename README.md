# dopagaki-legal

Android アプリ「**ドパガキ防止法**」(DOPAGAKI)の法務文書を GitHub Pages で公開するリポジトリ。

## 公開 URL

GitHub Pages 有効化後、以下の URL でアクセス可能になる:

- **インデックス**: `https://h01m1.github.io/dopagaki-legal/`
- **プライバシーポリシー**: `https://h01m1.github.io/dopagaki-legal/privacy.html`
- **利用規約**: `https://h01m1.github.io/dopagaki-legal/terms.html`
- **特定商取引法に基づく表記**: `https://h01m1.github.io/dopagaki-legal/legal.html`

## ファイル構成

```
.
├── index.html          ランディング(3 文書へのリンク)
├── privacy.html        プライバシーポリシー
├── terms.html          利用規約(Pro プラン条項含む)
├── legal.html          特定商取引法に基づく表記
├── assets/
│   └── style.css       共通スタイル(ディストピア風 CRT テーマ)
├── .nojekyll           Jekyll 処理を無効化(プレーン HTML として配信)
└── README.md           このファイル
```

## 未確定項目

各 HTML 内の `[TODO]` を、以下のタイミングで埋めること:

- **所在地**: GMO オフィスサポート 京都拠点の審査完了後
- **施行日 / 最終更新日**: 正式公開直前

## 編集方針

- すべてプレーンな HTML/CSS。ビルドプロセス不要。
- ローカル編集 → コミット → push で即時反映(GitHub Pages のビルドに数十秒)。
- 文言修正は各 `.html` を直接編集すれば良い。

## ライセンス

本リポジトリの内容は、ドパガキ防衛局が運営するアプリの法的開示のために公開しているものであり、複製・転載は想定していない。

---

運営: **ドパガキ防衛局**
連絡: m1n40suf1xless@gmail.com
