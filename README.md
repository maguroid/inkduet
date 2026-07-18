# inkduet

**AIと、書き上げる。**

inkduetは、人とAIが二人で一つの記事を仕上げる記事作成ワークスペースです。
粗い「伝えたいこと」から読者とストーリーを定め、調査、執筆、レビュー、修正を経て、
人間が公開可能だと判断できる原稿まで一貫して進めます。

AIによる代筆ではありません。AIは選択肢の生成、調査、執筆、レビュー、影響範囲の検出を担い、
書き手は伝えたいこと、ストーリー、修正の採否、完成を判断します。

## ドキュメント

- [プロダクトブリーフ](docs/product-brief.md)
- [編集工程の現行プロセスと課題定義](docs/editorial-workflow.md)
- [課題・機能仮説（BL Issues）](https://github.com/maguroid/inkduet/issues?q=is%3Aissue%20state%3Aopen%20label%3Akind%3Ahypothesis)
- [MVP実装単位（M Issues）](https://github.com/maguroid/inkduet/issues?q=is%3Aissue%20state%3Aopen%20label%3Akind%3Adelivery)
- [App Serverの技術設計](docs/app-server-architecture.md)

現在はハッカソンMVPの実装準備段階です。最初のMVPでは、一つの記事を
「伝えたいこと → ストーリー承認 → 初稿 → レビューと修正 → 完成判断」まで通します。
