## Local Modules

It is possible to add code from your local source code to your node_modules folder by including it as a dependency in your package.json.  Once you've done this you can require them from any file in your project without providing a path:

```js

// so last week
// let local_file = require("../../../service_rest/routes/main_route");

// so this week
let local_module = require("main_route");
```

It can be a little annoying when you are actively developing your local modules as you'll need to regularly clear and re-install your node_modules.  But this isn't bad to fix with gulp.js and some clever scripting.

___

### Resources

* The code in this folder
* [Arnaud's article](https://medium.com/@arnaudrinquin/build-modular-application-with-npm-local-modules-dfc5ff047bcc).   


___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>