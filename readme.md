---
layout: default
title: Readme of the git repository for the web-site of Theoretical Ecology and Evolution
---

# [Sources](https://github.com/banklab/banklab.github.io) for the lab [web-site of Claudia Bank's lab](https://banklab.github.io)

Most content is in the form of [kramdown](https://kramdown.gettalong.org/syntax.html), an extended markdown dialect. These markdown documents are converted to [HTML](https://eloquentjavascript.net/13_browser.html#h_n3OM6EV/KR) by [Jekyll](https://jekyllrb.com/).

Styles and layout are written in the SCSS syntax of the [SASS language](https://sass-lang.com/), a superset of CSS (cascading style sheets). The styles for this project can be found in the `/_sass` folder. Jekyll uses the file `assets/css/styles.scss` to import our main style file `_sass/main.scss` (which imports all our SCSS styles and loosely follows the [BEM rules](http://mikefowler.me/journal/2013/10/17/support-for-bem-modules-sass-3.3)).

Navigation is setup as a [basic list](https://jekyllrb.com/tutorials/navigation/#scenario-1-basic-list) in the file `_data/navigation.yml` – this determines the items and their order in the to navigation bar. The HTML for the navigation bar is defined in `_incudes/navigation.html` and imported into the only Jekyll layout defined here, in the file `_layouts/default.html`

# Attributions

## Images

Used in `resources.md` → [/resources](/resources) for

* Teaching
  * [https://unsplash.com/photos/V75YEqJp4pE](https://unsplash.com/photos/V75YEqJp4pE) from [@martinadams](https://unsplash.com/@martinadams)
* Tools
  * [https://unsplash.com/photos/gdL-UZfnD3I](https://unsplash.com/photos/gdL-UZfnD3I) from [@crissyjarvis](https://unsplash.com/@crissyjarvis)
* Media
  * [https://unsplash.com/photos/hRFg71vYTVk](https://unsplash.com/photos/hRFg71vYTVk) from [@markusspiske](https://unsplash.com/@markusspiske)

# To-do

## Import into the final repo `github.com/banklab/banklab.github.io`

As user `banklab`, login to github.com and then use this link [import project](https://github.com/new/import) and the following settings:

> Your old repository’s clone URL:  
`https://github.com/evoldyn/evoldyn.github.io.git`

> Your new repository details:
Owner/__Repository Name__  
banklab/`banklab.github.io`

![screen shot showing the import settings](/assets/img/misc/banklab.github.io_import.png)

When the import is finished you should find the new repo at [https://github.com/banklab/banklab.github.io](https://github.com/banklab/banklab.github.io) and the web-site at [https://banklab.github.io](https://banklab.github.io)

---

## Migrate domain from Wordpress (to Another Registrar) or have it point at new homepage

* [https://wordpress.com/support/move-domain/transfer-domain-registration/](https://wordpress.com/support/move-domain/transfer-domain-registration/)
* [https://www.namecheap.com/domains/transfer/](https://www.namecheap.com/domains/transfer/) (.org $14.98 / year)
* [https://www.inwx.de/en/org-domain](https://www.inwx.de/en/org-domain) (.org 11.91 € / year)

---

