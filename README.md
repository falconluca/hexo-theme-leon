# Leon 🌏

This is simple hexo blog theme, neither elegant ui nor beautiful animation. 

[Preivew leon](https://hexo-theme-leon-preview.pages.dev/)

**Leon requires Hexo 5.4.0 and above**

## Install

``` sh
git clone --depth 1 https://github.com/shaohsiung/hexo-theme-leon.git themes/leon
npm install hexo-generator-feed --save
npm install hexo-renderer-pug --save
```

## Enable

Modify `theme` setting in `_config.yml` to `leon`.

```diff
_config.yml
- theme: ...
+ theme: leon
```

Disable `highlight` and enable `prismjs` to highlight code in `_config.yml`

```diff
highlight:
  enable: false
prismjs:
  enable: true
```

## Run
``` sh
hexo clean
hexo g
hexo s
```

## Update

```sh
cd themes/leon
git pull
```


## LICENSE

MIT
