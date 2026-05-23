## ステップ 3: サイトを設定する

ホームページを更新できました。いい感じです :sparkles:

次は、見た目を整えるために少し **configuration** を追加しましょう。

### 理論: Jekyll と \_config.yml

Jekyll は `_config.yml` という名前のファイルを使って、サイト、テーマ、サイトタイトルや GitHub ハンドルなどの再利用可能なコンテンツの設定を保存します。詳しくは [Jekyll configuration documentation](https://jekyllrb.com/docs/configuration/) を参照してください。

このアクティビティでは、ブログ向けテーマである "minima" を使います。

### :keyboard: アクティビティ: サイトを設定する

1. `main` ブランチの `_config.yml` ファイルを開きます。
1. 右上でファイルエディターを開きます。
1. `_config.yml` ファイルに下のように表示されるよう、`theme:` を **minima** に設定して追加します。

   ```yml
   theme: minima
   ```

1. （任意）`title:`、`author:`、`description:` など、他の設定変数を変更してサイトをさらにカスタマイズできます。

   <details>
   <summary>例</summary><br/>

   ```yml
   theme: minima
   title: {{ login }}'s personal blog
   description: This is where I share cool stuff about my life
   author: {{ login }}
   ```

   </details>

1. 変更を `main` ブランチにコミットします。
1. 変更をコミットすると、Mona がこの演習の次のステップを準備します。

<details>
<summary>うまくいきませんか？</summary><br/>

- `main` ブランチの `_config.yml` ファイルを編集していることを確認してください。
- YAML の書式をもう一度確認してください。インデントとコロンは重要です。

</details>
