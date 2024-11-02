# ローコードSaaSのJavaScriptのエディターで編集体験を良くするためのTypeScript

管理画面のローコードSaaSであるベースマキナには、ユーザーがブラウザ上でJavaScriptを入力する機能があります。
このLTではJavaScriptのコードエディターで編集体験を良くするために、TypeScriptで型をつけて型情報の確認と補完を可能にしている以下のような例を紹介します。

- ユーザーが定義する関数の引数に、フォームの入力値から動的に生成した型をつける
- 組み込みのpackageからimportする関数に型をつける
- ユーザーが作成したデータを元に型をつける

コードエディターにはMonaco Editorを使用していますが、Monaco Editorに依存した話はほとんどなく、TypeScriptを使ったことのある方であれば楽しめる内容になる予定です。

---

- 非採択
- 5min
- 参考情報: <https://about.basemachina.com/news/feature-update-20240820#index_AQWRvQLx>
