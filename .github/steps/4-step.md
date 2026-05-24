## ステップ 4: ブログ記事を作成する

ホームページがいい感じになってきました！ :cowboy_hat_face:

### 理論: Jekyll のブログ記事とフロントマター

Jekyll は、特別な名前のファイルとフロントマターを使ってブログ記事を作成します。ファイル名は `_posts/YYYY-MM-DD-title.md` の形式にする必要があり、**フロントマター** に `title` と `date` を含める必要があります。

**フロントマター** は、ファイルの **先頭** に置く YAML セクションで、次のような形です。

```yaml
---
title: "私のブログへようこそ"
date: 2025-05-15
---
```

> [!NOTE]
> 詳しくは [Jekyll frontmatter documentation](https://jekyllrb.com/docs/front-matter/) を参照してください。

### :keyboard: アクティビティ: ブログ記事を作成する

1. `main` ブランチを開きます。
1. `Add file` ドロップダウンメニューをクリックし、`Create new file` をクリックします。
1. `_posts/YYYY-MM-DD-title.md` 形式に従ってファイル名を付けます。
1. `YYYY-MM-DD` を今日の日付に置き換え、必要であれば最初のブログ記事の `title` を変更します。
   > title を編集する場合は、単語の間にハイフン（-）があることを確認してください。
   > ブログ記事の日付が正しい日付形式に従っていない場合、エラーが発生し、サイトはビルドされません。詳しくは「[Page build failed: Invalid post date](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites)」を参照してください。
1. ブログ記事の先頭に、次の内容を入力します。

   ```yaml
   ---
   title: "YOUR-TITLE"
   date: YYYY-MM-DD
   ---
   ```

   1. `YOUR-TITLE` をブログ記事のタイトルに置き換えます。
   1. `YYYY-MM-DD` を今日の日付に置き換えます。
1. ブログ記事の簡単な下書きを入力します。あとからいつでも編集できます。
1. 変更を `main` ブランチにコミットします。
1. 変更をコミットすると、Mona がこの演習の次のステップを準備します。

<details>
<summary>うまくいきませんか？</summary><br/>

- ファイル名と日付形式をもう一度確認してください。
- フロントマターがファイルの一番上にあり、正しく書式設定されていることを確認してください。

</details>
