# Jekyll Bookmarlet

A simple HTML + JS page that allows you to post new articles to your GitHub-hosted Jekyll blog, using a browser.

## What is this?

If you host your Jekyll blog on GitHub, you can use jekyll-web-post to post new articles from a browser.

You can find more details here: [Post to your GitHub-hosted blog using a simple bookmarklet.](http://rogerstringer/2015/11/03/post-to-github-jekyll-using-a-bookmarklet/)

## Installation

Just copy `add-draft.html` to the root of your Jekyll blog source, and deploy. Then visit the page using your web browser, 
usually at `<url>/<base_url>/cms.html`.

Make sure you have `github.repo` and `github.branch` set in `_config.yml`. This is the repository and branch holding your
blog's source. For example:
```
github:
  repo: flybaseio/flybaseio.github.io
  branch: master
```

