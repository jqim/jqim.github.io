# Resizable layout prototype
This prototype uses an "element query library" to swap out some of the images when a container hits a certain size. For this library to function, the build must be viewed through a server.

- The element query libary:
https://github.com/marcj/css-element-queries

- The resizable layout is built with:
http://methvin.com/splitter/


### My project setup in the terminal (requires Sass and browsersync installed)
- http://sass-lang.com/
- http://www.browsersync.io/

1. Open terminal and navigate to the project root:
```
cd /Users/jamesma/Git/jqim.github.io/resizable-layout
```

2. Start Sass:
```
sass --watch sass/resize.scss:css/resize.css
```

3. Open a new tab for the next thing to run in:
```
ctrl-t to open new terminal tab
```

4. Start browser sync server:
```
browser-sync start --server --files "css/*.css, index.html"
```

5. A local host broswer window should now open with the project.