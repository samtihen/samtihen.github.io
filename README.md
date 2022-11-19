# samtihen.com (samtihen.github.io)

This is a personal site built using [Hugo](https://gohugo.io/), a static site generator.

The content is written in Markdown, and stored in the "content" folder.

The theme is called [m10c](https://github.com/vaga/hugo-theme-m10c), and was added as a git submodule to the "themes" directory.

## Build and deploy

1. [Install Hugo](https://gohugo.io/installation/)
2. Run server locally: hugo server (to include drafts -> hugo server -D)
3. Build to "docs" folder: hugo -d docs
4. Push to github, and configure GitHub Pages to deploy the "docs" folder.