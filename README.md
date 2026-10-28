# ネオ成実三昧

伊達成実専門サイト「成実三昧」(管理人 TAKEMI Shigino、http://shigezane.info/)の資料を、
Markdown CMS の形で再構築した公開サイトです。

- 公開URL: https://oosawak.github.io/neo-shigezane-zanmai/
- 横スクロール年表: https://oosawak.github.io/neo-shigezane-zanmai/nenpyou-timeline.html

## ライセンスと出典

収録コンテンツは、原典サイト「成実三昧」のライセンスに基づき、
クリエイティブ・コモンズ 表示-継承 2.1 日本(CC BY-SA 2.1 JP)で公開します。
原典の著作権は TAKEMI Shigino さんに帰属します。各記事に出典を明記しています。
第三者の方の寄稿テキスト・写真は原典のライセンスでも対象外のため、
転載せず元ページへのリンクに置き換えています。

カバー画像は AI(Muse)が作成したイラストです。

## 仕組み

`content/posts/shigezane/` の Markdown を GitHub Actions が JSON に変換し、
`docs/` から GitHub Pages で配信する静的サイトです(本人の Markdown CMS と同じ仕組み)。
