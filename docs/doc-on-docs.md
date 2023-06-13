---
layout: default
title: Documentation on Docs
nav_order: 10
---

If [Jekyll] is installed on your computer, you can also build and preview the documentation site *locally*. This lets you test the changes before committing them, and avoids having to wait for GitHub Pages to deploy them.[^1]

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse **Just the Docs** documentation][Just the Docs] to learn more about how to use this theme.

----

[^1]: [It can take up to 10 minutes for changes to your site to be published after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).


[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
