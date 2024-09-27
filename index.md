---
title: Home
layout: home
---

<html>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');

:root {
  --yle-blue-color:             rgb(0, 180, 200);
  --violet-color:               rgb(124, 89, 250);
  --deep-blue-color:            rgb(19, 22, 37);
  --deep-blue-alpha-color:      rgba(19, 22, 37, 0.8);
  --deep-blue-alpha-less-color: rgba(19, 22, 37, 0.6);
  --black-color:                rgb(0, 0, 0);
  --white-color:                rgb(255, 255, 255);
  --breaking-color:             rgb(233, 14, 67);
}

.main {
  display: flex;
  justify-content: center;
}

.planssi1 {
  display: flex;
  flex-direction: column;
  background: var(--deep-blue-color);
  padding: 1em;
  margin: 1em .25em 1em .25em;
  align-items: right;
  border-radius: 0.2vw;
  font-weight: 700;
  color: white;
  font-family: "Montserrat";
  overflow: hidden;
}
.kentat {
  padding: 1em 1em 1em 1em;
}

.kentta_1 {
  background: var(--yle-blue-color);
  padding-right: 1em;
  text-align: left;
}

.kentta_2 {
  background: var(--violet-color);
  padding-right: 1em;
  text-align: left;
}

.kentta_3 {
  background: var(--breaking-color);
  padding-right: 1em;
  text-align: left;
}
</style>
<div id="main" class="main">
  <div class="planssi1">
    <div class="kentat kentta_1"><div id="f0">Kenttä 1</div></div>
    <div class="kentat kentta_2"><div id="f1">Kenttä 2</div></div>
    <div class="kentat kentta_3"><div id="f2">Kenttä 3</div></div>
  </div>
</div>
</html>
More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
