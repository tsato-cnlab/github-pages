{%- set all_passed = (results_table | selectattr("passed") | length) == (results_table | length) %}

{%- if all_passed %}

## ステップ {{ step_number }} - 合格 ✅

{%- else %}

## ステップ {{ step_number }} - 失敗 ❌

{%- endif %}

{%- if all_passed %}
<img src="https://octodex.github.com/images/inflatocat.png" align="right" height="150px" alt="ステップに合格したことを示す Inflatocat の画像" />
{%- else %}

<img src="https://octodex.github.com/images/spidertocat.png" align="right" height="100px" alt="ステップに失敗したことを示す Spidertocat の画像" />
いくつかのチェックが失敗しました。下の結果を確認して、もう一度試してください。

バグを見つける時間です！ 🤔
{%- endif %}

| 状態 | 説明 |
| ---- | ---- |

{%- for row in results_table %}
| {% if row.passed -%}✅ - 合格{%- else -%}❌ - 失敗{%- endif %} | {{ row.description }} |
{%- endfor %}

{%- if tips and tips.length %}

### ヒント

{%- for tip in tips %}

- {{ tip }}
  {%- endfor %}

{%- endif %}
