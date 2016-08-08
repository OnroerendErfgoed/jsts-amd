jsts amd build
======================
This repository is used for internal distribution of the [JSTS](https://github.com/bjornharrtell/jsts) library, 'an 
ECMAScript 2015 library of spatial predicates and functions for processing geometry conforming to the 
Simple Features Specification for SQL published by the Open Geospatial Consortium'. 

The repository provides a build version of the js library that can be imported as a bower dependency in other projects.

###install dependencies:
```
cd <project dir>
npm install
```

##how to build:
Custom build is not necessary, the npm package contains a dist folder

##version numbering:
the version numbers follow the corresponding jsts version

##how to release a new build:
+ Update jsts using npm
+ Copy jsts.min.js from <project dir>/node_modules/jsts/dist/ to the <project dir> folder and rename to jsts.js
+ Push to git
+ Run 'bower update jsts-amd' in the projects that use this dependency