## jQuery Mobile Flat-UI Theme

Theme for jQuery Mobile based on [Flat-UI](http://designmodo.com/demo/flat-ui/).
Forked from [ququplay/jquery-mobile-flat-ui-theme](https://github.com/ququplay/jquery-mobile-flat-ui-theme) because the last update was more than a year ago, no support for jQuery Mobile 1.4 onwards. Essentially, the project appears to be abandoned in favour of new premium themes. Hence…

- Updated to support the latest jQuery Mobile 1.4.5
- Slight refinements to design including font weights and shadows
- Replaced internal PNG icons with SVG icons. Faster loading themes and resolution independent! 
- New, nicer looking loader animation

<img src="https://m1.behance.net/rendition/modules/152637041/disp/271b1c52d1fab00a70b1244cbf3950b4.jpeg" width=49%> <img src="https://m1.behance.net/rendition/modules/152637097/disp/6e655a54a4ef36d42afccb57c67dd77f.jpeg" width=49%>

Refer to [tlkh/transitionmetals](https://github.com/tlkh/transitionmetals) or [tlkh/fightingships](https://github.com/tlkh/fightingships) to see implementation and how to modify iOS 7 and iOS 8 status bar colour.

View the [live demo](http://tlkh.github.io/jquery-mobile-flat-ui-theme/).

## Usage

Copy `jquery.mobile.flatui.css`, fonts and images from `generated` folder to your project.
Include link to `jquery.mobile.flatui.css`

```html
 <link rel="stylesheet" type="text/css" href="jquery.mobile.flatui.css" />
```

## Setup

In order to add a new swatch or colors you can add a new stylus file under `src/stylus/swatches/` and run [grunt](http://gruntjs.com/) from your command line.

- brew install node
- npm install -g grunt-cli
- cd to project's folder
- npm install
- grunt watch
- start modifying css/stylus files

##License:

[The WTFPL License](http://en.wikipedia.org/wiki/WTFPL) inherited from [ququplay/jquery-mobile-flat-ui-theme](https://github.com/ququplay/jquery-mobile-flat-ui-theme)