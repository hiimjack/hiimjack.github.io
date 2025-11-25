# website

## init

```bash
hugo new site src
git submodule add https://github.com/luizdepra/hugo-coder.git src/themes/hugo-coder
```

## development

```bash
cd src
rm -rf public resources ; sleep 1 ; hugo server -D --disableFastRender
```
