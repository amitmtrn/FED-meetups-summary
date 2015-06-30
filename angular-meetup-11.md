#angular meetup 11

backand.com
saas for backend

## the productive developer

productive developer /= good developer

---

* terminal can save you time - windows cygwin
  * zsh http://ohmyz.sh
  * scm breeze
  * http://github.com/ndbroadbent/scm_breeze
  * auto jump
  * use alias
* npm modules
  * **localtunnel - http://localtunnel.me**
  * http-server
  * json-server
  * n - node version manager
* browser
  * hotkeys
  * extentions
    * octotree
    * JSONView
    * EditThisCookie
* code editor
  * hotkeys
  * live templates
  * macro
* OS
  * airdrop - mac
  * screenshots - mac
  * reassign caps lock

## angular & webpack

**module bundler**

```
  npm i -g webpack
```

```
npm i -g webpack-dev-server
```

Create `webpack.config.js`

```js
  module.exports = {
    context: __dirname + '/src',
    entry: '.app,js',
    module: {
      loaders: [
        { test:/\.js$/, exclude:'./node_modules', loader: 'babel' }
        { test:/\.less$/, exclude:'./node_modules', loader: 'style!css!less' }
      ]
    }
  };
```

index.html
```
<script src="/bundle.js"></script>
```
