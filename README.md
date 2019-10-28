# xaringan_gh

A example repo to demonstrate how to host xaringan slides on github page


## How to use:

- Create a repo with xaringan slide with the following files(Or clone this one):
    - xaringan_example.rmd, your xaringan slide
    - index.md, for the homepage of github page, see the index.md for an example.
- In rstudio, knit the xaringan slides.
- Push everything to github
- Setup github pages: `Settings` - `Github Pages`- `source: master branch`, (Optional: choose a jekyll theme)
- Done, the slides can be viewed online at `https://tcgriffith.github.io/xaringan_gh/xaringan_example`

```
Old instructions.

- Clone this repo to your github account.

- setup github pages: `Settings` - `Github Pages`- `source: master branch`

- Done! The slides can be viewed online at the url on the setting page. For example, https://tcgriffith.github.io/xaringan_gh/ is the link for this repo.
```

## Update on 191027:

I've recently learned a few more things about xaringan/gh pages/jekyll so it's time to simplify the process to deploy xaringan on gh pages.