[![Board Status](https://dev.azure.com/mfalhim/cb47e38e-4b24-466e-abc5-a88396e9b7ac/8b3ec819-683d-4df7-9f2d-111b5b6983a1/_apis/work/boardbadge/319dabb7-d661-4c07-806f-ef222d20f20b)](https://dev.azure.com/mfalhim/cb47e38e-4b24-466e-abc5-a88396e9b7ac/_boards/board/t/8b3ec819-683d-4df7-9f2d-111b5b6983a1/Microsoft.RequirementCategory)
[![Travis CI Status](https://travis-ci.org/intel-android/androidhub.svg?branch=master)](https://travis-ci.org/intel-android/androidhub)
[![Join the chat at https://gitter.im/intel-android/androidhub](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/intel-android/androidhub?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

### Required Tools
> These tools need to be installed on your machine, hopefully they're already there. We also expect you to have a GitHub account, and have used CLI tools a bit.

- [ImageMagick](http://www.imagemagick.org/script/binary-releases.php)
- [Node/NPM](https://nodejs.org/)
- [Roots](http://roots.cx/) `npm i roots -g`
- [Bower](http://bower.io/) `npm i bower -g`
- Git

### Getting Started
- run `npm i && bower i` to kick off installation of project and front end deps
- run `roots watch` to begin dev development with live reload

### Author App Overview / Folder Architecture
- `data/`  
Each .yaml files found in this folder is turned into a json object and passed to jade templates.
- `posts/`  
Holds authors posts/articles. Each author has their own folder which holds their images and articles.

### Contributing!?
Whether you want to write articles or help fix bugs, it's as easy as fork and pull request. For more information, see the [author readme](https://github.com/intel-android/androidhub/blob/master/authors_readme.md).

### Testing
`npm test`
