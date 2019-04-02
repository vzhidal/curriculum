# Practical Tasks

To accomplish that task, you'll need to watch
[several screencasts](https://1drv.ms/f/s!AsZKQfymLyQuhO5NZiCdui5qbY6SLQ)
from HTML/CSS trainings. 


## General Requirements

* Don’t use LESS and SASS/SCSS. This task is to focus on HTML and CSS 
  design, not front-end builds and preprocessors.
* Make use of HTML semantic elements. 
* Pay attention to container-content separation while designing HTML and
  CSS structure. It’s briefly described [here](https://github.com/stubbornella/oocss/wiki). 
* Use [BEM methodology](https://ru.bem.info/methodology/) of CSS 
  architecture, but don’t fall for it blindly. 
* Use [BEM’s file structure](https://ru.bem.info/methodology/filestructure/).
  There are several options described, you will have to choose any but
  be ready to justify your choice. 
* The images extracted using Photoshop should be stored in a consistent
  format (JPEG, PNG). The choice of the format should be based on the
  image itself: for example, if it needs transparency, it has to be PNG.
* Use
  [PerfectPixel extension](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?hl=ru)
  for self-checking on how close you are to actual mockups. Bear in mind
  that there are cases when pixel-perfect makeup harms CSS readability
  and reusability. There are cases when it’s better to stick to some
  clear proportions/distances. 
* Though ultimately it may seem to contradict BEM, make use of either
  [normalize.css](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?hl=ru)
  or [reset.css](https://meyerweb.com/eric/tools/css/reset/). 
* Use icon fonts for icons. It’s recommended to use some tool to
  generate the CSS that you can add to your page (like
  [icomoon](https://icomoon.io/app/#/select)) rather than use some
  cloud-based solution (e.g. font awesome). 
* GitHub provides a simple static page hosting called
  [GitHub Pages](https://pages.github.com/). This is convenient for
  checking so use it. 
* Apply [CSScomb](http://csscomb.com/) tool to lint and order CSS rules.
  The general recommendation of ordering CSS rules can be found
  [here](https://css-tricks.com/poll-results-how-do-you-order-your-css-properties/).
  ([basic configuration](../assets/csscomb.json))


## List of Tasks Groups

| name                                                   | short description                                     | priority | estimation (h) | requirements |
|--------------------------------------------------------|-------------------------------------------------------|----------|----------------|--------------|
| [static-web-page](./static-web-page/readme.md)         | create a static web page using an attached layout     | 1        | 20-30          |              |
| [responsive-web-page](./responsive-web-page/readme.md) | create a responsive web page using an attached layout | 1        | 40-50          |              |



