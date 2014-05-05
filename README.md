1) Including other files
	file1.js
		var mymodule = require('/mymodule.js');
		my module.js
		module.exports={}
2) Core modules
	var fs = require('fs');
	fs file system
	os operating system
	child.process = process


3) npm
	var ___ = require('underscore')


Running the update for npm

curl -L http://npmjs.org/install.sh | sudo sh

	It will prompt for a password in a cryptic way

//

npm view moment version
npm init  //creates package.json file

node test1.js (will print any log methods in the console in test1.js)
npm install moment --save //adds a dependency to package.json


npm init
npm install
npm update
npm view moment
npm view underscore
npm search jquery
npm install moment --save //adds dependency to package.json
npm install underscore --save 