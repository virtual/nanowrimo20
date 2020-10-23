# NaNoWriMo

## Development
- Install Hugo: `brew install hugo`
- Install [Serif Theme](https://github.com/JugglerX/hugo-serif-theme) 
- May need to temporarily comment out `themes` in `.gitignore`, then run `cd themes` and `git submodule add https://github.com/zerostaticthemes/hugo-serif-theme`
- Note: may need to remove `themes/hugo-serif-theme/content/contact.md`

## Run
- Run server from project root: `hugo server`

## Build site
- [Hugo command](https://gohugo.io/commands/hugo/): `hugo`
- `rm -rf docs`
- `mv public docs`
- commit to git repo 

## New Post
- `hugo new characters/char-name.md`
- `hugo server -D` (show drafts)
