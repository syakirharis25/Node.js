# Node.js
My works related to Node.js

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Checking Node.js version.](#nodeversion)
4. [Checking npm version.](#npmversion)
5. [Cannot find module error solution.](#modulesolution)
6. [Node.js conferences.](#conferences)
7. [GitHub notes.](#github)
8. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="nodejs.png" height="150"> 
Node.js is an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside of a browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm, unifying web-application development around a single programming language, rather than different languages for server- and client-side scripts. <br /><br />

Node.js is built on V8 JavaScript engine, same as what Google Chrome use right now. It was written in C++ programming language, essentially allows developers to run JavaScript code on the server.

Though .js is the standard filename extension for JavaScript code, the name "Node.js" doesn't refer to a particular file in this context and is merely the name of the product. Node.js has an event-driven architecture capable of asynchronous I/O. These design choices aim to optimize throughput and scalability in web applications with many input/output operations, as well as for real-time Web applications (e.g., real-time communication programs and browser games). <br />

The Node.js distributed development project was previously governed by the Node.js Foundation, and has now merged with the JS Foundation to form the OpenJS Foundation, which is facilitated by the Linux Foundation's Collaborative Projects program.

<a name="references"></a>
## 2. Official references websites. <br />
Node.js official website : https://nodejs.org <br />
Node.js official documentation : https://nodejs.org/en/docs/ <br />

**_Node.js documentation by nodejs.org_** <br />
Node.js v12.16.0 Documentation by nodejs.org : https://nodejs.org/dist/latest-v12.x/docs/api/ <br />
Node.js v12.16.0 Documentation for Path by nodejs.org : https://nodejs.org/dist/latest-v12.x/docs/api/path.html <br />
Node.js v12.16.0 Documentation for File System by nodejs.org : https://nodejs.org/dist/latest-v12.x/docs/api/fs.html <br />
Node.js v12.16.0 Documentation for Events by nodejs.org : https://nodejs.org/dist/latest-v12.x/docs/api/events.html <br />
Node.js v13.9.0 Documentation for Global Objects by nodejs.org : https://nodejs.org/docs/latest/api/globals.html <br />
Node.js v13.9.0 Documentation for Assert by nodejs.org : https://nodejs.org/api/assert.html <br />

**_Node.js schools_** <br />
W3Schools educational website : https://www.w3schools.com <br />
TutorialsTeacher educational website : https://www.tutorialsteacher.com <br />
Stack Overflow questions and answer website : https://stackoverflow.com <br />
DevMountain is a private coding bootcamp : https://devmountain.com <br />

**_Node.js questions and answers by Stack Overflow_** <br />
What is process.env.PORT in Node.js? by Stack Overflow : https://stackoverflow.com/questions/18864677/what-is-process-env-port-in-node-js <br />
Is MongoDB reliable? [closed] by Stack Overflow : https://stackoverflow.com/questions/3505141/is-mongodb-reliable <br />
Error: Cannot find module 'uuid' by Stack Overflow : https://stackoverflow.com/questions/43865189/error-cannot-find-module-uuid <br />
response.writeHead and response.end in NodeJs by Stack Overflow : https://stackoverflow.com/questions/14243100/response-writehead-and-response-end-in-nodejs <br />
Node JS Error: ENOENT by Stack Overflow : https://stackoverflow.com/questions/9047094/node-js-error-enoent <br />
What is the purpose of Node.js module.exports and how do you use it? by Stack overflow : https://stackoverflow.com/questions/5311334/what-is-the-purpose-of-node-js-module-exports-and-how-do-you-use-it <br />

**_Node.js related technologies_** <br />
V8 engine : https://v8.dev <br />
ECMAScript® 2020 Language Specification : https://tc39.es/ecma262 <br />
WebAssembly Specification : https://webassembly.github.io/spec/core <br />
Node Package Manager | npm : https://www.npmjs.com <br />
jQuery : https://jquery.com <br />
Chrome JSON Viewer : https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh <br />
Heroku is a cloud platform as a service supporting several programming languages : https://www.heroku.com <br />
The Heroku CLI : https://devcenter.heroku.com/articles/heroku-cli <br />
Git : https://git-scm.com <br />

**_Node.js packages_**
Express : https://expressjs.com <br />
Fastify : https://www.fastify.io <br />
nodemon : https://nodemon.io <br />
@babel/node : https://babeljs.io/docs/en/next/babel-node.html <br />

**_Node.js v12.15.0 documentation by nodejs.org_**
Events by nodejs.org : https://nodejs.org/dist/latest-v12.x/docs/api/events.html <br />

**_Node.js documentation by nodejs.org_**
What is require? by nodejs.org : https://nodejs.org/en/knowledge/getting-started/what-is-require/ <br />

**_Node.js documentation by W3Schools_**
Node.js server.listen() Method by W3Schools : https://www.w3schools.com/nodejs/met_server_listen.asp <br />
Node.js http.createServer() Method by W3Schools : https://www.w3schools.com/nodejs/met_http_createserver.asp <br />

**_Node.js documentation by TutorialsTeacher_**
Node.js EventEmitter by TutorialsTeacher : https://www.tutorialsteacher.com/nodejs/nodejs-eventemitter <br />

**_Node.js related articles_**
Understanding EventEmitter in Node.js With a UseCase by Ganesh Mani : https://dev.to/ganeshmani/understanding-eventemitter-in-node-js-with-a-usecase-441m <br />
Top 20 Best NodeJS Frameworks For Developers in 2020 by Rownok Ara :https://www.ubuntupit.com/best-nodejs-frameworks-for-developers <br />
Express, Koa, Meteor, Sails.js: Four Frameworks Of The Apocalypse by Chuoxian Yang : https://www.toptal.com/nodejs/nodejs-frameworks-comparison <br />
Node.js Frameworks Comparison for Your Back-end Solution: Express.js, Meteor.js, Sails.js, and more : https://www.altexsoft.com/blog/engineering/node-js-frameworks-comparison-for-your-back-end-solution-express-js-meteor-js-sails-js-and-more/ <br />
Experimenting with Web Assembly and Node.js by Bryan Hughes : https://dev.to/azure/experimenting-with-web-assembly-and-nodejs-40f4 <br />
NestJS why use? by Filipe Mazzon : https://www.linkedin.com/pulse/nestjs-why-use-filipe-mazzon/ <br />
Why I choose NestJS over other Node JS frameworks by S M Asad Rahman
 : https://medium.com/monstar-lab-bangladesh-engineering/why-i-choose-nestjs-over-other-node-js-frameworks-6cdbd083ae67 <br />
Why node is the future? by Tarun Nagar : https://yourstory.com/mystory/why-node-is-the-future <br />
IBM and Node.js: A look at the past, present, and future : https://developer.ibm.com/blogs/ibm-and-nodejs-our-history-present-and-future/ <br />
Popular Stack: Full Stack VS Mean Stack VS MERN Stack by WaftTech : https://www.wafttech.com/blog/popular-stack-full-stack-vs-mean-stack-vs-mern-stack<br />
Unique identifiers generation in Node.js : https://blog.abelotech.com/posts/generate-unique-identifier-nodejs-javascript/ <br />
Understanding module.exports and exports in Node.js by James Hibbard : https://www.sitepoint.com/understanding-module-exports-exports-node-js/ <br />
What is the difference between npm run dev and npm run production? : https://laracasts.com/discuss/channels/javascript/what-is-the-difference-between-npm-run-dev-and-npm-run-production <br />
How to view the HTML source code of a web page by Computer Hope : https://www.computerhope.com/issues/ch000746.htm <br />
Node.js | join() function by GeeksforGeeks : https://www.geeksforgeeks.org/node-js-join-function/ <br />
Reading a file with Node.js - blocking and non-blocking by Gabor Szabo : https://code-maven.com/reading-a-file-with-nodejs <br />

**_Node.js developers_**
Ganesh Mani : https://github.com/ganeshmani <br />
Saurabh Mhatre : https://github.com/smhatre59 <br />
Bryan Hughes : https://github.com/nebrius <br />
S M Asad Rahman : https://github.com/asad-mlbd <br />
Vigneshwer Dhinakaran : https://github.com/dvigneshwer <br />
Jon Byrum : https://github.com/jbyrum <br />
Sepideh Setayeshfar : https://github.com/ssetayeshfar <br />
Nahid Samsami : https://github.com/nsamsami <br />
James Hibbard : https://github.com/jameshibbard <br />
Gabor Szabo : https://github.com/szabgab <br />

<a name="nodeversion"></a>
## 3. Checking Node.js version.
To check Node.js version, simply do this command.
```
$ node --version
```

<a name="npmversion"></a>
## 4. Checking npm version.
To check npm version, simply do this command.
```
$ npm --version
```

<a name="modulesolution"></a>
## 5. Cannot find module error solution.
If there was error stating this message.
```
Error: Cannot find module 'C:\Users\username\Desktop\Node.js\os_demo'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:981:15)
    at Function.Module._load (internal/modules/cjs/loader.js:863:27)
    at Function.executeUserEntryPoint [as runMain] (internal/modules/run_main.js:74:12)
    at internal/main/run_main_module.js:18:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
```

Then you need to find the package.json file in your working folder and change your main to your working file.
```
"main": "workingfile.js",
```

Then under terminal, type this command.
```
$ npm install
```

Make sure to install all the related npm dependencies.

<a name="conferences"></a>
## 5. Node.js conferences.
Node.js conference by International JavaScript Conference : https://javascript-conference.com/node-js <br />

<a name="github"></a>
## 6. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Node.js.git
$ cd Node.js/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 7. GitHub repository calculation.
```-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
JavaScript                     345           7682           8425          31781
JSON                           177              0              0          23331
Markdown                       209           8654              2          21976
TypeScript                      12             93            289            369
DOS Batch                        9             18              0            135
PowerShell                       9              9             27            126
Bourne Shell                     9             18              0            117
YAML                             7              3              0             68
HTML                             3              9              0             36
make                             1             14              4             32
CSS                              1              0              0              4
-------------------------------------------------------------------------------
SUM:                           782          16500           8747          77975
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc

adding GitHub repository calculation
