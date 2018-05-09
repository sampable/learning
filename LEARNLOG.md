2018-05-05
- [x] init a node.js directory with "npm init"
- [x] /usr means shared, read-only data for every users
- [x] /usr/bin means programs which are not system programs (mean not used to booting or reparing the system)
- [x] shell script is more general terms, while bash script is one kind of shell script
- [x] ~/.bash_profile is the script file executed before launch of login shells
- [x] login shells is the shell required to login and performance actions on behalf of logged in user
- [x] interactive shells is the shell that input and output connected to terminal 
- [x] to remove package from sublime text 3: Preference -> Package Control -> Remove Package
- [x] "git push -u" means set upstream when push
- [x] markdown header need space after ###
- [x] markdown checkbox need space between [ and ]
- [x] create symbolic link to /usr/local/bin in order to support subl command
- [x] hello world express framework (node.js)
- [x] use "npm install --no-save" when the package not suppose to be deployed to production (e.g. debug heapdump), or you want to try the package first before deciding to use it or not
- [x] "npm install --save" will add the package to the dependencies list, which is that package will be installed when we run "npm install"
- [x] create node.js module using exports
- [x] import node.js module using require()
- [x] how to serve static file to public ? `app.use('asset', express.static('public'))` will serve files in "public" foler to "http://baseurl/asset" url
- [x] what is nodemon ? nodemon is a wrapper for node which will monitor any source code change happen in node.js application and restart the app automatically
- [x] how to generate basic files and folders for express ? "express --view=pug myapp"

2018-05-06
- [x] what is loader for webpack ? preprocessor for file in webpack
- [x] "open ." will open finder for current directory
- [x] what the differents between "ng serve" and "ng build" ? "ng serve" will compile the code and start an http server, while "ng build" will build the app to an output directory

2018-05-07
- [ ] try gsamokovarov/jump

2018-05-09
- [x] what is .bashrc ? setup script(s) run on every interactive shell start
- [x] what is `jump shell` ? setup scripts for gsamokovarov/jump integrating bash shell
- [x] what is `eval` in bash ? take a string as parameter and execute it like input directly in terminal
- [ ] what is the meaning of $ in `eval "$(jump shell)"`
- [x] test multiple lines code 
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```