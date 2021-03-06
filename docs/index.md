
    var app = express.createServer();
    
    app.get('/', function(req, res){
        res.send('Hello World');
    });

    app.listen(3000);

## Features

  * Robust routing
  * Redirection helpers
  * Focus on high performance
  * View rendering and partials support
  * Environment based configuration
  * Session based flash notifications
  * Built on [Connect](http://extjs.github.com/Connect)
  * [Executable](executable.html) for generating applications quickly

## Contributors

The following are the major contributors of Express (in no specific order).

  * TJ Holowaychuk ([visionmedia](http://github.com/visionmedia))
  * Ciaran Jessup ([ciaranj](http://github.com/ciaranj))
  * Aaron Heckmann ([aheckmann](http://github.com/aheckmann))

## More Information

  * [Google Group](http://groups.google.com/group/express-js) for discussion
  * Follow [tjholowaychuk](http://twitter.com/tjholowaychuk) on twitter for updates
  * Annotated source [documentation](api.html)
  * View the [Connect](http://github.com/extjs/Connect) repo for middleware usage
  * View the [Connect Wiki](http://wiki.github.com/extjs/Connect/) for contrib middleware
  * View the [examples](http://github.com/visionmedia/express/tree/master/examples/)
  * View the [source](http://github.com/visionmedia/express)
