# ローコードSaaSのUXを向上させるためのTypeScript

管理画面のローコードSaaSであるベースマキナには、JavaScriptで組み込みの関数の呼び出しや条件分岐などの処理を書いて、ワークフローを作成できる機能があります。

このセッションでは、この機能のユーザー体験を向上させるためにどのようにTypeScriptを活用しているかを紹介します。

以下が話す予定の内容です。

- ブラウザ上のMonaco Editorを使ったコードエディターで、ユーザーが定義した関数や組み込みの関数に型をつけて補完を可能にする
- 組み込みの関数の引数の型をzodのスキーマで定義して、実行前に引数の値をバリデートし、日本語のエラーメッセージを表示する

など

一部Monaco Editorとzodの話も含みますが、大部分はTypeScriptの機能を使った話です。
特定のライブラリの機能を使う部分には都度説明を入れるので、TypeScriptを使ったことのある方であれば楽しめる内容になる予定です。

---

- 30min
