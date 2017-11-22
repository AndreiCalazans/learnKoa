# learnKoa
Using Koa js examples



### quick doc

### Getting started with flow

* you need a parser 
  - babel-preset-flow
  - babel-cli

  just add this below to your babelrc file.
``` 
  "presets": ["flow"]
```

once you have the above install run the following commands
`yarn add flow-bin --dev`
`flow init` // creates a flow config file
`yarn run flow`  // run flow checker

make sure you install an flow extension in your IDE.


### GETTING STARTED WITH ESLINT

Install eslint either locally or globally

`yarn global add eslint``

to start run
`eslist --init` // will ask a few question to generate .eslintrc file


## Configure eslint for flow

install
```
yarn add babel-eslint --dev
yarn add eslint-plugin-flowtype --dev
```

then include these in your eslintrc file

`"parser": "babel-eslint",`
``` 
"extends": [
    "eslint:recommended",
    "plugin:flowtype/recommended"
], 
```
``` 
"plugins": [
    "react",
    "flowtype"
],
``` 

