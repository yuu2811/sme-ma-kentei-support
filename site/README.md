# サポート・プライバシーのページ（`site/`）

App Store が必須とするプライバシーポリシーの URL とサポートの URL のための静的なページ。
**公開リポ yuu2811/sme-ma-kentei-support** に置いて GitHub Pages で配る（このリポジトリは非公開）。

| ファイル | 用途 | URL |
|---|---|---|
| `index.html` | トップ（マーケティング URL） | https://yuu2811.github.io/sme-ma-kentei-support/ |
| `privacy.html` | 利用規約・プライバシーポリシー（必須） | …/privacy.html |
| `support.html` | サポート・よくある質問（必須） | …/support.html |
| `style.css` | 共通の見た目（アプリと同じ色・ダークモード対応） | |

URL は `store/asc-plan.json`・アプリの購入シートと概要（`app/main.js` の `SITE`）が使う（`tests/store.test.mjs` が照らす）。
データの扱いを変えたら、アプリの中の文・掲載文・審査メモと同じ変更でここも直し、公開リポへ反映してから審査に出す
（審査員が読むのは公開中のページ）。
