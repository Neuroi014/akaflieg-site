# 【実習】学術飛行サークル - Akaflieg

本サイトは講義課題として制作したものです。

慶應義塾大学 湘南藤沢キャンパス（SFC）の講義「Webデザインとマネジメント」の個人課題として、代表が自分のサークルを題材に作ったサイトです。

- 日本語版：https://neuroi014.github.io/akaflieg-site/
- 英語版：https://neuroi014.github.io/akaflieg-site/en/

## ページ

| ページ | ファイル | 内容 |
|---|---|---|
| トップ | `index.html` | サークルの紹介、主な活動、活動の記録、お知らせ |
| 概要 | `about.html` | 基本情報、目的、名前の由来、実機についての方針、沿革 |
| 活動内容 | `activities.html` | 2026年度の活動、講習会の記録 |
| 参加案内 | `join.html` | 参加までの流れ、対象、活動場所、会費、よくある質問 |
| お問い合わせ | `contact.html` | Discord、メール、個人情報の取り扱い |

英語版は `en/` に同じ5ページがあります。

## 作り

- 素の HTML と CSS だけで作っています。JavaScript は使っていません。
- 公開は GitHub Pages です。main ブランチの内容がそのまま公開されます。
- `css/tokens.css` に色・文字の大きさ・余白の値を、`css/base.css` に部品の見た目をまとめています。
- 各ページの HTML は、手元の Python スクリプトから書き出しています。スクリプトはこのリポジトリには含めていません。HTML を直接直すと、次の書き出しで上書きされます。
- 画面の幅に合わせて、パソコンとスマートフォンの両方で読めるようにしています。

## 画像

- 写真（`img/hero-glider-*.webp`、`img/report-0712-*.webp`、`img/ogp.jpg`）は、2026年7月12日の講習会で代表が撮影したものです。位置情報は消してあります。
- 図（`img/learning-cycle.svg`、`img/learning-cycle-en.svg`）は自作です。
- ロゴ（`img/logo-compact.svg`、`img/favicon.svg` など）はサークルのものです。

## 生成AIの利用

制作には Claude Code（Anthropic）を使いました。構成、文章、HTML と CSS を対話しながら作り、内容と見た目は代表が確かめて決めています。

## 連絡先

お問い合わせは、サイトの[お問い合わせページ](https://neuroi014.github.io/akaflieg-site/contact.html)からお願いします。
