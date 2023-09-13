# issue

```bash
npm install
npm run dev
```

see error:

```
[plugin:vite:import-analysis] Failed to resolve import "geojson" from "pages/index.vue". Does the file exist?
```

[error message](error-message.png)

---

set `"verbatimModuleSyntax": false` in `tsconfig.json` and `npm run dev` again -- now everything renders fine.
