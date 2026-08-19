# 田村仁浩 CV サイト

「目次ナビ＋日英切替」の構成です。

## ファイル

| ファイル | 内容 |
|---|---|
| `index.html` | ご挨拶（日本語トップ） |
| `cv.html` | 経歴 |
| `interest.html` | 研究の興味 |
| `papers.html` | 業績 |
| `index_en.html` / `cv_en.html` / `interest_en.html` / `papers_en.html` | 上記の英語版 |
| `style.css` | 全ページ共通のスタイル |
| `img/photo.jpg` | 顔写真 |

## 公開のしかた（GitHub Pages）

1. GitHub で `<ユーザ名>.github.io` という名前のリポジトリを作る
2. このフォルダの中身をすべてリポジトリ直下に置いて push する
3. `https://<ユーザ名>.github.io/` で公開される（反映まで数分）

## 差し替えるところ

- `img/photo.jpg` を実際の顔写真に置き換える（縦長・幅300px程度で十分）
- **英語版のCV(PDF)**: 用意した PDF を `cv_tamura.pdf` という名前でリポジトリ直下（HTMLと同じ場所）にアップロードする。`index_en.html` と `cv_en.html` の「Download CV (PDF)」リンクが自動でそれを指す。別名にする場合は両ファイルの `href="cv_tamura.pdf"` を書き換える
- 各ページ冒頭の `Last modified: Jul 24, 2026` を更新日に書き換える
- サイト名は「アンドロイドの人らしさ / Human-Likeness of Androids」。変える場合は全8ファイルの `sitetitle` と `<title>` を書き換える
- 業績が増えたら `papers.html` / `papers_en.html` の `<p class="pub">` をコピーして追加する
- 所属学会が決まったら `cv.html` / `cv_en.html` の「（準備中）」を置き換える
