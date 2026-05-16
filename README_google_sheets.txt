# Google Sheets / Apps Script メモ

index.html の上部にある次の2箇所を必要に応じて差し替えます。

```
const SURVEY_URL = "https://forms.gle/xxxxxxxx";
const LOG_ENDPOINT = "";
```

- SURVEY_URL は最後のアンケート用GoogleフォームURLです。
- LOG_ENDPOINT はGoogle Apps ScriptのウェブアプリURLです。
- 空欄のままでも、端末内localStorageとCSV/JSON出力は使えます。
