将src/like_button.js 的jsx语法解析为javascript语法，适用于浏览器

```
npx babel --watch src --out-dir . --presets react-app/prod
```

Now, to minify a file called `like_button.js`, run in the terminal:

```
npx terser -c -m -o like_button.min.js -- like_button.js
```

