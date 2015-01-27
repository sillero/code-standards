# code-standards
From this gist -> https://gist.github.com/sillero/fbbc83aaaa31142672dd

###Guides
http://codeguide.co/  
https://github.com/styleguide  
https://github.com/airbnb/javascript  
https://github.com/polarmobile/coffeescript-style-guide  

**inuit.css = BEM + OOCSS + awesomeness**   
https://github.com/csswizardry/inuit.css/  
https://github.com/inuitcss/getting-started  
http://jsfiddle.net/user/inuitcss/fiddles/  
http://csswizardry.com/2014/05/grouping-related-classes-in-your-markup/  
http://csswizardry.com/2014/03/naming-ui-components-in-oocss/

**mobile-first + content breakpoints**  
http://www.mightyminnow.com/2013/11/what-is-mobile-first-css-and-why-does-it-rock/


###Editor Configuration
http://editorconfig.org/  
- *Atom package*: https://github.com/sindresorhus/atom-editorconfig#readme  
- *Sublime package*: https://github.com/sindresorhus/editorconfig-sublime#readme  

###Linters and editor packages 

**Editor packages (required)**
- Atom: Linter 
- Sublime: SublimeLinter

**Sass**
- Atom package: Linter Scss Lint
- Sublime package: SublimeLinter-contrib-scss-lint
- Install CLI: gem install scss-lint
- Options: https://github.com/causes/scss-lint/blob/master/lib/scss_lint/linter/README.md

**JavaScript**
- Atom package: Linter Jshint
- Sublime package: SublimeLinter-jshint
- Install CLI: npm install -g jshint
- Options: http://www.jshint.com/docs/options/

**CoffeeScript**
- Atom package: Linter Coffeelint
- Sublime package: SublimeLinter-coffeelint
- Install CLI: npm install -g coffeelint
- Options: http://www.coffeelint.org/#options


###Images
@font-face (depends on browser support)  
SVG + PNG fallback (safest, but needs more work, even on JS for handling mouse/touch events)
In the future, possibly use SVG Stacks
- background-image: url(sprites.svg#icon-id)
- \<img src="sprites.svg#icon-id"\>

http://benfrain.com/image-sprites-data-uris-icon-fonts-v-svgs/


###Architecture
http://dev.ghost.org/css-at-ghost/  
http://www.ebaytechblog.com/2014/10/02/dont-build-pages-build-modules/
