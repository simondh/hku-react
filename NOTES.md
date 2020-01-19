#Hong Kong University React training course
## Course Notes

##Front-End Web Development with React
[here](Front-End Web Development with React)

###NPM

Start a project (i.e. my own project, not an existing package):  
`$ mkdir /npm-proj1; cd /npm-proj1` 

`$ npm init`  
Creates:  
* package.json  (qv)

`npm install` creates or updates node_modules and package-lock.json - this lists EVERY node module needed by the `npm install` history. See it after just installing lite-server (!)

###Lite Server
`$ npm install lite-server --save-dev`

--save-dev saves the package install into package.json, as a dependency for DEV only, use `--save` for prod use.  
Creates `node_modules`, qv. HUGE, even from just one `npm install`