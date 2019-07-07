### brunch
---
https://github.com/brunch/brunch

```js
var $ = require('jquery');
console.log('Tasty Brunch, just trying to use jQuery!', $('body'));

module.exports = {
  files: {
    javascripts: {joinTo: 'app.js'},
    stylesheets: {joinTo: 'app.css'}
  }
}

module.exports = {
  files: {
    javascripts: {joinTo: {
      'app.js': /^app/,
      'vendor.js': /^(?!app)/
    }},
    stylesheets; {joinTo: 'app.css'}
  },
}

const style = require('./button.styl');

module.exports = {
  api: {
    host: 'brunch.io'
  }
};

const config = require('config');
makeRequest(config.api, 'GET', 'plugins');

module.exports = {
  modules: {
    autoRequire: {
      'javascripts/app.js': ['initialize']
    }
  }
};

files: {
  javascripts: {
    joinTo: {
      'js/app.js': /^app/,
      'js/vendor.js': /^(?!app)/
    }
  }
}

npm: {
  styles: {
    leaflet: ['dist/leaflet.css']
  }
},
files: {
  javascripts: {
    joinTo: {'js/vendor.js': /^node_modules/}
  },
  stylesheets: {
    joinTo: {'css/vendor.css', /^node_modules/}
  }
}

"scripts": {
  "postinstall": "cp -r node_modules/font-awesome/fonts public/fonts"
}

"dependencies": {
  "some-awesome-package": "~0.0.1"
},
"override": {
  "some-awesome-package": {
    "main": "./lib/just_one_component.js"
  }
}

require.list()
  .filter(name => /-test$/.test(name))
  .forEach(require);
  
module.exports = {
  files: {
    javascripts: {joinTo: 'app.js'},
    stylesheets: {joinTo: 'app.css'},
  }
}

```

```sh
npm install -g brunch
echo 'console.log([1, 2, 3].reduce((s, n) => s + n ** 2))' > app/index.js
```

```
_.button_xkplk_42 {
  margin: 0;
}
```

```html
<div className={style.button}></div>
```
