jQuery.kooy
==========

jQuery.kooy is a jQuery based input method library for malayalam phonetic input.

Most of the code of this plugin is adapted from [`swanalekha-ml.js`](https://github.com/smc/input-methods/tree/master/swanalekha-js) which developed by [Santhosh Thottingal](https://github.com/santhoshtr). 

This plugin is completely deployed on [vanmaram](http://www.vanmaram.com) online malayalam dictory. 


Quick start
-----------

```bash
git clone https://github.com/pshanoop/kooy.git
```

To add kooy support to the textarea of a web page:

```js
$( 'textarea' ).kooy();
```

jQuery.kooy support all jQuery selector. But kooy plugin will working only on editable fields. Kooy plugin adds a class `kooy` to all element when kooy is enabled. So you can add any custom `css` to it to notify user kooy is activated.

#### Disable kooy

```js
$('textarea').kooy('disable');
```

#### Enable kooy

By default kooy plugin will be enabled. Call this after disable function call.
```js
$('textarea').kooy('enable');
```

#### Distroy kooy

```js
$('textarea').kooy('distroy');
```

Example
-------

See [an example](http://www.vanmaram.com/manglish) page
where jquery.kooy in action.

To try the example locally, after checking out the code, start a local webserver
to serve the files. This is very easy.

If you have python installed, run
```bash
python -m SimpleHTTPServer
```

Alternatively, many programming languages provide one liner commands to start a simple http static servers. You can use [any one of them](https://gist.github.com/willurd/5720255).


and, you can access examples from
```bash
http://localhost:8000/index.html
```
Alternatively you can use tools like webfsd. If you know how to use advanced
web servers like Apache or Nginx, you already know how to put the code in a
webserver.

License
-------
This project is licensed with MIT license. See the license
files in the source code for more details.
