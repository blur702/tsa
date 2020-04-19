# Bootstrap 4 theme

## Features:

* Includes Bootstrap 4 library (JS and CSS)
* Includes Bootstrap 4 breakpoints
* Bootstrap controls within user interface
* Comes with `no subtheme mode` (unless template override required)
* Style guide with most of Boostrap components navigate to `http://[your site url]/themes/contrib/bootstrap4/style-guide`

## SASS compilation:

* SASS compilation is no longer in the theme.
* Use [Bootstrap4 Tools](https://www.drupal.org/project/bootstrap4_tools) module

## Installation

### Using composer

`composer require drupal/bootstrap4`

## Subtheme

* If you require subtheme (usually if you want to override templates), 
    see [subtheme docs](_SUBTHEME/README.md).

* You can create subtheme by running `bash bin/subtheme.sh [name] [path]`,
    e.g. `bash bin/subtheme.sh b4subtheme ..`

* Interface subtheme creation is coming to [Bootstrap4 Tools](https://www.drupal.org/project/bootstrap4_tools) module

## Development and patching

- Install development dependencies by running `npm install`
- To lint SASS files run `npm run lint:sass` (it will fail build if lint fails)
- To compile SASS run `sass scss/style.scss css/style.css` (requires [SASS compiler](https://sass-lang.com/install))
