# Simple Grid System
This is a lightweight, responsive and modern grid system based in flexbox.

### Getting Started

Currently, there is only one way to use this small framework in your project. I'm still working on new improvements.

#### Install manually
Download the compiled and minified version of the [CSS File](https://github.com/rafaelcmrj/simple-grid-system/tree/master/dist/)

And include `simple-grid-system.min.css` located in `/dist` in your website or Web app &lt;head&gt; part.

`<link rel="stylesheet" href="simple-grid-system.min.css" />`

### Compiling custom version

You will need [LESS](http://lesscss.org/) to compile your custom version.

After install LESS, edit your breakpoints at `/less/breakpoints.less` and run:

```
lessc build.less dist/simple-grid-system.css
```

For minified versions:
```
lessc build.less dist/simple-grid-system.min.css --clean-css
```

Feel free to submit a pull request.