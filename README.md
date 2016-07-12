jsts amd build
======================
Used for internal distribution.



###install dependencies:
```
cd <project dir>
npm install
```

##how to build:
Custom build is not necessary, the npm package contains a dist folder


##how to release a new build:
+ Update jsts using npm
+ Copy jsts.min.js from <project dir>/node_modules/jsts/dist/ to the <project dir> folder and rename to jsts.js
+ Push to git
+ Run 'bower update jsts-amd' in the projects that use this dependency