# website

## init

```bash
hugo new site src
git submodule add https://github.com/luizdepra/hugo-coder.git src/themes/hugo-coder
```

## update theme

```bash
cd src/themes/hugo-coder
git fetch --tags
git checkout v1.2
cd ../..
git add themes/hugo-coder
git commit -m "Update hugo-coder theme to v1.2"
```

## local development

```bash
cd src
rm -rf public resources ; sleep 1 ; hugo server -D --disableFastRender
```
