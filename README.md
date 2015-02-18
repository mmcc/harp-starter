# Harp + Grunt + Browserify boilerplate

I found myself setting this up manually the first few times, so I decided to go ahead and make things official with a little
boilerplate repo. There's nothing fancy here, simply a Grunt file that includes tasks for running a [Harp](http://harpjs.com)
project along with [Browserify](http://browserify.com).

### Usage

```
$ git clone https://github.com/mmcc/harp-starter.git && cd harp-starter
$ npm install
$ grunt dev
```

Once `grunt dev` is running, you can start working. A local preview is running on port 9000.

### Setup

I use the basic Harp directory set up to start with:

```
- public
  - css
    - main.scss
  - js
  - _layout.ejs
  - index.ejs
- src-js
  - app.js
```

It's important to note that the `bundle.js` file generated by Browserify (and placed in `public/js`) is gitignored.
