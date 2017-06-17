Fork of https://github.com/mahsu/MariOCaml, compiled using [BuckleScript](https://github.com/bucklescript/bucklescript) instead of js_of_ocaml.

[Play it live!](http://chenglou.github.io/MariOCaml/)

```
git clone https://github.com/chenglou/MariOCaml.git
cd MariOCaml
npm install
npm start
```

Then, if you're using Safari, simply open `docs/index.html`. **No bundling needed! Safari supports native es6 modules, which we can compile to**. If not, run `npm run pack-for-non-safari` then open that html page.
