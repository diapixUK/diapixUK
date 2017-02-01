# DiapixApp

[![Join the chat at https://gitter.im/diapixUK/diapixUK](https://badges.gitter.im/diapixUK/diapixUK.svg)](https://gitter.im/diapixUK/diapixUK?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
The diapixUK is a dialogue elicitation technique and set of materials developed by Baker and Hazan (2011) and based on the Diapix task of van Engen et al (2010).

It consists of 12 ‘spot the difference’ picture tasks that have to be solved cooperatively by pairs of participants. For more information, [see our website](http://www.phon.ucl.ac.uk/project/kidLUCID/diapix.php)!

# More about Diapix
Check out our [wiki](https://github.com/diapixUK/diapixUK/wiki)!
If you are interested, the wiki is larely based on our [report](https://drive.google.com/file/d/0B1iMVcQUdo2oV0Vhb2hsLUd1UlU/view?usp=sharing).

# Development
## Install ionic via npm
```
npm install -g ionic
cd DiapixApp
npm install
ionic emulate android (or ionic run android or npm start, or heroku local)
```
Make sure your AVM emulator is configured through Android Studio.

## we usin SASS
it's in `scss/style.scss`, and run `gulp` or `gulp sass` to get it into minified version, linked from `index.html`

## we usin jQuery, Node & Vanilla JS
it's in `www/js/main.js`. Server stuff is `server.js`, `www/js/socket.js`

## Heroku + Postgres
they handle the db stuff and env config vars

## Dependencies
Just run `npm install`.
- gulp
- ionic UI components
- npm / node obvs
- jQuery
- handlebars for custom re-usable semantic templates
- sequelize
- express
just read `package.json` man i cba

### Useful links for help with node + homebrew + ionic
If you get stuck trying to make node play with ionic on OSX, etc etc, see below!
- [1](http://stackoverflow.com/questions/28017374/what-is-the-suggested-way-to-install-brew-node-js-io-js-nvm-npm-on-os-x)
- [2](http://stackoverflow.com/questions/26406484/brew-doctor-warning-unbrewed-header-files-were-found-in-usr-local-include)
- [3](http://stackoverflow.com/questions/34335340/angular2-quickstart-npm-start-is-not-working-correctly)
