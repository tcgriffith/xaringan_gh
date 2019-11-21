# Xaringan_gh

A example repo to demonstrate how to host xaringan slides on github page


## How to use:

- Create a repo(Or clone this one) with xaringan slide and the following files:
    - xaringan_example.rmd, your xaringan slide
    - index.md, for the homepage of github page, see the index.md for an example.
- In rstudio, knit the xaringan slides.
- Push everything to github
- Setup github pages: `Settings` - `Github Pages`- `source: master branch`, (Optional: choose a jekyll theme)
- Done, the slides can be viewed online at `https://{account}.github.io/{repo_name}/{xaringan_slide_filename}`


For example
- The URL for this xaringan_example slide is at: https://tcgriffith.github.io/xaringan_gh/xaringan_example
- I embedded the xaringan slide into the github page(index.md). Using this method you could embed the slide in a [blogdown post](https://github.com/rstudio/blogdown) as well.(~~Or if you are creative, embed it into another xaringan slide recursively and get your own russian doll~~





## Update on 191027:

I've recently learned a few more things about xaringan/gh pages/jekyll so it's time to simplify the process to deploy xaringan on gh pages.
