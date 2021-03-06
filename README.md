# Milsymbol-generator
Military symbol generator based on milsymbol.js

![Milsymbol Generator](https://raw.githubusercontent.com/spatialillusions/milsymbol-generator/master/milsymbol-generator.png?raw=true)

## Live deployed example
You can find an online version at https://spatialillusions.com/unitgenerator/

## Deploying locally
After downloading this or the original repository, all that is needed is to run `npm install` in the root folder and then run `npm run build`. No errors should come up, only warnings. After this, all it takes is to open `unitgenerator/index.html` in (almost) any browser.

## Disclaimer
This is still in development and is still missing quite a lot of functionality compared to the current symbol generator. Please provide feedback and ideas as issues.

At the moment it uses the [development version of milsymbol](https://github.com/spatialillusions/milsymbol) from the master branch to get access to all the symbol information from milstd.js that is included with milsymbol. This will change as soon as it is possible to use a released version of milsymbol. 

For the UI [Material Design Components](https://github.com/material-components/material-components-web/) are used, but I have tried to separate logic from UI, so you should be able to reuse as much as possible, and it is possible to initiate a single standard generator in any element on a web page. The API will be improved and updated.
