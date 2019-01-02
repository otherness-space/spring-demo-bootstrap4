# Read Me

## Contents

##### [About](#about-) \| [Who](#who-) \| [What](#what-) \| [Where](#where-) \| [Why](#why-) \| [How](#how-)

#### [Notes](#notes-)

##### [Note 1](#note-1-) \| [Note 2](#note-2-)

#### [Appendix](#appendix-)

##### [.gitattributes](#gitattributes-) \| [.gitignore](#gitignore-) \| [.exclude](#exclude-)

### [Credits](#credits-)

* * *

## About [≪](#read-me)

This is a starter repo.

### Who [≪](#read-me)

Your Mom's blank repo.

### What [≪](#read-me)

Spring Demo 2019

-   [x] A
-   [ ] B
    -   [ ] C
    -   [ ] D
-   [ ] E

### Where [≪](#read-me)

Built local with an Atom editor on a Win 10 64 host and `git` on a VboxVM for an Ubuntu guest .

### Why [≪](#read-me)

Blank

### How [≪](#read-me)

* * *

## Notes [≪](#read-me)

### Note 1 [≪](#read-me)

### Note 2 [≪](#read-me)

* * *

## Appendix [≪](#read-me)

### .gitattributes [≪](#read-me)

> Git attribute data also allows you to do some interesting things when exporting an archive of your project.

```markdown
.git                    export-ignore
.gitignore              export-ignore
.gitattributes          export-ignore
.travis.yml             export-ignore
codesniffer.ruleset.xml export-ignore
```

<https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes#Exporting-Your-Repository>

### .gitignore [≪](#read-me)

```
_site
.sass-cache
node_modules
# blank*
# assets/vendor

####################################################
# https://help.github.com/articles/ignoring-files/ #
####################################################

###################
# Compiled source #
###################
*.com
*.class
*.dll
*.exe
*.o
*.so

############
# Packages #
############
# it's better to unpack these files and commit the raw source
# git has its own built in compression methods
*.7z
*.dmg
*.gz
*.iso
*.jar
*.rar
*.tar
*.zip

######################
# Logs and databases #
######################
*.log
*.sql
*.sqlite

######################
# OS generated files #
######################
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db
*.nfo

##################
# Ruby.gitignore #
##################

Gemfile
/tmp/

## Environment normalization:
/.bundle/
/vendor/bundle
/lib/bundler/man/

# for a library or gem, you might want to ignore these files since the code is
# intended to run in multiple environments; otherwise, check them in:
Gemfile.lock
# .ruby-version
# .ruby-gemset

# unless supporting rvm < 1.11.0 or doing something fancy, ignore this:
.rvmrc

####################
# Jekyll.gitignore #
####################

_site/
.sass-cache/
.jekyll-cache/
.jekyll-metadata

################################################
# npm_modules.gitignore dependency directories #
################################################

# node_modules/
```


*   [.gitignore manual](https://git-scm.com/docs/gitignore)
*   `[.gitignore manual](https://git-scm.com/docs/gitignore)`
*   [Example .gitignore files](https://github.com/github/gitignore)
*   `[Example .gitignore files](https://github.com/github/gitignore)`
*   [The Octocat has a Gist containing some good rules to add to this file.](https://gist.github.com/octocat/9257657)
*   `[The Octocat has a Gist containing some good rules to add to this file.](https://gist.github.com/octocat/9257657)`

### .exclude [≪](#read-me)

*   [Explicit repository excludes](https://help.github.com/articles/ignoring-files/#explicit-repository-excludes)
*   `[Explicit repository excludes](https://help.github.com/articles/ignoring-files/#explicit-repository-excludes)`

* * *

### Credits [≪](#read-me)

Third party resources applied in this repo. Each resource uses a GPL compatible license. The resources are listed according to each individual license, as noted, and have links where applicable.

-   This repository began as a fork of following the steps in [https://simpleit.rocks/ruby/jekyll/tutorials/how-to-add-bootstrap-4-to-jekyll-the-right-way/](https://simpleit.rocks/ruby/jekyll/tutorials/how-to-addbootstrap-4-to-jekyll-the-right-way/).
    -   [![GitHub forks](https://img.shields.io/github/forks/marcanuy/jekyll-bootstrap4.svg?style=social)](https://github.com/marcanuy/jekyll-bootstrap4/network) [![GitHub stars](https://img.shields.io/github/stars/marcanuy/jekyll-bootstrap4.svg?style=social)](https://github.com/marcanuy/jekyll-bootstrap4/stargazers) [![GitHub license](https://img.shields.io/github/license/marcanuy/jekyll-bootstrap4.svg?style=social)](https://github.com/marcanuy/jekyll-bootstrap4/blob/master/LICENSE)
-   This repository is my fork with my edits to suit my repo [https://github.com/otherness-space/jekyll-bootstrap4#testing-locally](https://github.com/otherness-space/jekyll-bootstrap4#testing-locally).
    -   [![GitHub forks](https://img.shields.io/github/forks/otherness-space/jekyll-bootstrap4.svg?style=social)](https://github.com/otherness-space/jekyll-bootstrap4/network) [![GitHub stars](https://img.shields.io/github/stars/otherness-space/jekyll-bootstrap4.svg?style=social)](https://github.com/otherness-space/jekyll-bootstrap4/stargazers) [![GitHub license](https://img.shields.io/github/license/otherness-space/jekyll-bootstrap4.svg?style=social)](https://github.com/otherness-space/jekyll-bootstrap4/blob/master/LICENSE)
-   Bootstrap v4.1.3
    -   Sleek, intuitive, and powerful front-end framework for faster and easier web development.
    -   Copyright (c) 2011-2018 Twitter, Inc.
    -   Copyright (c) 2011-2018 The Bootstrap Authors
    -   [![Build Status](https://img.shields.io/travis/twbs/bootstrap/v4-dev.svg?style=social)](https://travis-ci.org/twbs/bootstrap) [![GitHub release](https://img.shields.io/github/release/twbs/bootstrap.svg?style=social)](https://github.com/twbs/bootstrap) [![npm version](https://img.shields.io/npm/v/bootstrap.svg?style=social)](https://www.npmjs.com/package/bootstrap) [![Gem version](https://img.shields.io/gem/v/bootstrap.svg?style=social)](https://rubygems.org/gems/bootstrap) [![GitHub forks](https://img.shields.io/github/forks/twbs/bootstrap.svg?style=social)](https://github.com/twbs/bootstrap/network) [![GitHub stars](https://img.shields.io/github/stars/twbs/bootstrap.svg?style=social)](https://github.com/twbs/bootstrap/stargazers) [![GitHub license](https://img.shields.io/github/license/twbs/bootstrap.svg?style=social)](https://github.com/twbs/bootstrap/blob/v4-dev/LICENSE) [![devDependency Status](https://img.shields.io/david/dev/twbs/bootstrap.svg?style=social)](https://david-dm.org/twbs/bootstrap?type=dev)
-   jQuery v3.3.1
    -   jQuery JavaScript Library
    -   Copyright JS Foundation and other contributors, [https://js.foundation/](https://js.foundation/)
    -   [![Build Status](https://img.shields.io/travis/jquery/jquery.svg?style=social)](https://travis-ci.org/jquery/jquery) [![GitHub release](https://img.shields.io/github/release/jquery/jquery.svg?style=social)](https://github.com/jquery/jquery) [![npm version](https://img.shields.io/npm/v/jquery.svg?style=social)](https://www.npmjs.com/package/jquery) [![GitHub forks](https://img.shields.io/github/forks/jquery/jquery.svg?style=social)](https://github.com/jquery/jquery/network) [![GitHub forks](https://img.shields.io/github/forks/jquery/jquery.svg?style=social)](https://github.com/jquery/jquery/network) [![GitHub stars](https://img.shields.io/github/stars/jquery/jquery.svg?style=social)](https://github.com/jquery/jquery/stargazers) [![GitHub license](https://img.shields.io/github/license/jquery/jquery.svg?style=social)](https://github.com/jquery/jquery/blob/master/LICENSE.txt)
-   Popper.js v1.14.6
    -   A library used to position poppers in web applications.
    -   A popper is an element on the screen which "pops out" from the natural flow of your application.
    -   Common examples of poppers are tooltips, popovers, and drop-downs.
    -   Copyright © 2016 Federico Zivolo and contributors
    -   [![Build Status](https://img.shields.io/travis/FezVrasta/popper.js.svg?style=social)](https://travis-ci.org/FezVrasta/popper.js/branches) [![GitHub release](https://img.shields.io/github/release/FezVrasta/popper.js.svg?style=social)](https://github.com/FezVrasta/popper.js) [![npm version](https://img.shields.io/npm/v/popper.js.svg?style=social)](https://www.npmjs.com/package/popper.js) [![GitHub forks](https://img.shields.io/github/forks/FezVrasta/popper.js.svg?style=social)](https://github.com/FezVrasta/popper.js/network) [![GitHub stars](https://img.shields.io/github/stars/FezVrasta/popper.js.svg?style=social)](https://github.com/FezVrasta/popper.js/stargazers) [![GitHub license](https://img.shields.io/github/license/FezVrasta/popper.js.svg?style=social)](https://github.com/FezVrasta/popper.js/blob/master/LICENSE.md)
-   PrismJS v1.15.0
    -   Prism is a lightweight, extensible syntax highlighter, built with modern web standards in mind. It’s used in thousands of websites, including some of those you visit daily.
    -   Copyright (c) 2012 Lea Verou
    -   [https://prismjs.com/](https://prismjs.com/download.html#themes=prism-dark&languages=markup+css+clike+javascript+apacheconf+c+asciidoc+csharp+bash+cpp+coffeescript+clojure+ruby+css-extras+django+docker+elixir+markup-templating+erlang+flow+git+go+less+haskell+java+json+julia+latex+markdown+lisp+makefile+erb+objectivec+pascal+perl+php+php-extras+sql+powershell+prolog+properties+scss+puppet+pure+python+r+jsx+typescript+rest+rust+sass+scala+scheme+plsql+swift+yaml+tsx+vim+wiki&plugins=line-highlight+line-numbers+show-invisibles+custom-class+toolbar+jsonp-highlight+highlight-keywords+previewers+command-line+normalize-whitespace+keep-markup+copy-to-clipboard)
    -   [![Build Status](https://img.shields.io/travis/PrismJS/prism.svg?style=social)](https://travis-ci.org/PrismJS/prism) [![GitHub release](https://img.shields.io/github/release/PrismJS/prism.svg?style=social)](https://github.com/PrismJS/prism) [![npm version](https://img.shields.io/npm/v/prismjs.svg?style=social)](https://www.npmjs.com/package/prismjs) [![GitHub forks](https://img.shields.io/github/forks/PrismJS/prism.svg?style=social)](https://github.com/PrismJS/prism/network) [![GitHub stars](https://img.shields.io/github/stars/PrismJS/prism.svg?style=social)](https://github.com/PrismJS/prism/stargazers) [![GitHub license](https://img.shields.io/github/license/PrismJS/prism.svg?style=social)](https://github.com/PrismJS/prism/blob/master/LICENSE)
