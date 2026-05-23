{% set socials_text -%}
{%- if exercise_title -%}
「{{ exercise_title }}」GitHub Skills ハンズオン演習を完了しました！ 🎉
{%- else -%}
GitHub Skills ハンズオン演習を完了しました！ 🎉
{%- endif %}

{{ repository_url }}

#GitHubSkills #OpenSource #GitHubLearn
{%- endset -%}

<div align="center">

# 🎉 おめでとうございます、{{ login }} さん！ 🎉

<img src="https://octodex.github.com/images/welcometocat.png" height="200px" />

### 🌟 演習を完了しました！ 🌟

## 🚀 成果を共有しましょう

**新しく身につけたスキルを見せて、他の人の学びも後押ししましょう！**

<a href="https://twitter.com/intent/tweet?text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20X-1da1f2?style=for-the-badge&logo=x&logoColor=white" alt="Share on X" />
</a>
<a href="https://bsky.app/intent/compose?text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20Bluesky-0085ff?style=for-the-badge&logo=bluesky&logoColor=white" alt="Share on Bluesky" />
</a>
<a href="https://www.linkedin.com/feed/?shareActive=true&text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Share on LinkedIn" />
</a>

### 🎯 次は何をしますか？

**この勢いのまま進みましょう！**

[![](https://img.shields.io/badge/演習に戻る-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)]({{ issue_url }})
[![GitHub Skills](https://img.shields.io/badge/GitHub%20Skills%20を見る-000000?style=for-the-badge&logo=github&logoColor=white)](https://learn.github.com/skills)

*何かを作りながら学ぶことほど良い学び方はありません！* 🚀

</div>

---

&copy; 2025 GitHub &bull; [行動規範](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT ライセンス](https://gh.io/mit)
