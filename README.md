Webpack Tree Shaking example

```
npm i
npm run build
cat dist/bundle.js | grep 'AAAAAA' -> not empty, as expected
cat dist/bundle.js | grep 'BBBBBB' -> empty, as expected
cat dist/bundle.js | grep 'CCCCCC' -> not empty, why?
```
