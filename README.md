# In The Beginning...
A startpoint framework for bower + gulp prototype projects.


#### prerequisites:
- install [node.js](https://nodejs.org/en/)
```shell
sudo npm install node -g
```


#### usage: install
```shell
$ sudo npm install
```

##### extras...
- install gulp-sass (`sudo npm install --global gulp-sass`)


#### usage: setup
+ add `gulpfile.js` into root project directory

_mod `gulpfile.js`_
- line 18 -- change watch directory pwd `app/css/**/*.css`
- line 20 -- change watch directory pwd `*.html`
- line 22 -- add additional directories and working files needed for your project


#### usage: run
```shell
gulp
```
