# [css](reworkcss/css)

```js
css.parse(`@import url("https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700&display=swap");`)
```
import urlの中に;があったら、エラーが出る
→Import match Regexを修正する
