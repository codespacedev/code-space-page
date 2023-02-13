# Code Space Web Page

The [Webseite](https://code-space.dev) is created with
[Hugo](https://gohugo.io).

### Requirements

* [hugo](gohugo.io) (Website builder framework)
  * MacOs `brew install hugo`
  * Windows `choco install hugo -confirm`

### Start website locally

* `git submodule update --recursive --remote`
* `hugo server -w`

### Shortcuts
* make sure you are operating in root the folder of the project
* Add chapter `hugo new --kind chapter MyChapter/_index.md` (`chapter` is a template)
* Add new page `hugo new MyChapter/my-first-post.md`
* Delete page: just delete the specific `.md` files from `website/content`
* Predefined [Variables and Params](https://gohugo.io/variables/)
* Predefined [Functions](https://gohugo.io/functions/)
* CLI [Commands](https://gohugo.io/commands/)

### Deployment

The GitHub
Action [github-pages](https://github.com/europace/duck-tech-wiki/blob/main/.github/workflows/github-pages.yml) deploys
automatically every change from the `main` branch. See also: [Adding new theme](https://gohugo.io/getting-started/quick-start/#step-3-add-a-theme)

