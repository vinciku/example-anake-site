## Cmd to build site
/user/bin/hugo -s hugo new ../../docset/test.md

## Tools to generate pdf
WKHTMLTOPDF

## Download theme(ananke)
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke

### Download all hugo theme
git clone --depth 1 --recursive https://github.com/gohugoio/hugoThemes.git themes

## add theme to config
echo  'theme = "ananke"' >> config.toml

## Start Server(very important)
hugo server -D


