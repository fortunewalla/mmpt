### mmpt - Minimal Modified Primer Template

#### Description:

A unique minimal template for creating a static website quickly using GitHub Pages based on the default Primer Theme.

#### Feature set:

* Dark/Light Theme Mode Switcher

* Latex through Katex

#### Use cases:

* To write articles through Markdown and Latex with dark theme built-in.

* To quickly publish using GitHub Pages without worrying about any settings. 

* To be able to write articles in offline mode with just a text editor without any extra software.

* To also maintain an archive of readable markdown pages.

#### Minimum requirements:

* Basic knowledge of `git`, GitHub & Markdown

* A public GitHub Repository with Github Pages Activated

#### Typical workflow:

* Use this repository as a template. _Click on the green "Use This Template" Button_

* Activate GH Pages in the settings. _Go to Settings --> Pages --> Source --> master branch_

* Replace the contents of `index.md` file with your own content.

* _Optional:_ Create other markdown `example1.md` files and add their links `<example1.md>` as per your choice to build up a website.

* `git push` to your repo to rebuild the website automatically through GH Actions

#### Template Files:

`_includes/head-custom.html` needed to initialise location of style file `main.scss` 

`_layouts/default.html` needed to initialise katex code and light/dark theme button.

`css/main.scss` needed to define light/dark themes colors.

`scripts/mode-switcher.js` script to toggle the light/dark theme button.

`CNAME` needed to redirect to a domain.

#### Base Theme:

Primer is a Jekyll theme for GitHub Pages. Follow this theme's instructions for further customization.

<https://www.github.com/pages-themes/primer>

Primer Demo: <https://pages-themes.github.io/primer/>

_© 2022 Fortune Walla_