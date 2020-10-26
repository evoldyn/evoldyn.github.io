# [Jekyll](https://jekyllrb.com/) sources for the lab web-site

Most content is in the form of [kramdown](https://kramdown.gettalong.org/syntax.html), an extended markdown dialect. These markdown documents are converted to [HTML](https://eloquentjavascript.net/13_browser.html#h_n3OM6EV/KR) by [Jekyll](https://jekyllrb.com/).

Styles and layout are written in the SCSS syntax of the [SASS language](https://sass-lang.com/), a superset of CSS (cascading style sheets). The styles for this project can be found in the `/_sass` folder. Actually, Jekyll uses the file `assets/css/styles.scss` to import our main style file (which imports all the SCSS styles and loosely follows [BEM rules](http://mikefowler.me/journal/2013/10/17/support-for-bem-modules-sass-3.3)).

