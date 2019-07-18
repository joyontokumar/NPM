<h1><b>NPM</b></h1>
The full meaning of npm -> node package manager. there are all word have a meaning. bellow all are describe : in  other word npm is the world's largest Software Registry. 

<b>Node : </b>
that means there are a lot of code like javascript.

<b>Package : </b>
when one or more javascript are boundle in one thing that called package. that means if you want to a javascritp plugin then you create a
seperate seperate file to easy way to handle your project. when your project is completed then you can boundle this seperate seperate file
in one folder that called a package.

<b>Manager : </b>
manager means node and package maintaining work.

<b> Why Node Package Manager : </b>
once upon a time javascritp only work in browser, but this time we can run this our local computer machine . this only can possible if you install your computer node.js software . by the way npm is the default tools in node js . suppose node js is the code editor and npm is the extra feature this feature easy way to code run . that means npm is a tools that way we can easy way to run code and install package. the npm most extra feature is
many other developer to develop many kind of program for other develop to develop their own application. so we can easily use this code.

<b>Project Setup : </b>
ok ! now we create a project . fist of all go the desktop and create a folder and folder name is suppose myproject. then we want to initalise your node js. so we can write our command prompt

<pre><code>npm init</code></pre>




when you type this command then we can see the command put to some information. it easy and the information you have to put like
<pre><code>
name (my-new-project):
version (1.0.0):
description:
entry point (index.js):
git repository:
author:
license (MIT):
</code></pre>

. if you avoaid this process information and set
default normal information then you can write our command prompt 

<pre><code>npm init -y </code></pre>

y stand for yes . then we see our project directory a file this name package.json. then we can see package.json file look like this.

<pre>
  <code>
    {
  "name": "my-new-project",
  "version": "1.0.0",
  "description": "My New Project description.",
  "main": "index.js",
  "repository": {
    "url": "https://example.com/your-username/my-new-project",
    "type": "git"
  },
  "author": "Your Name <you@example.com>",
  "license": "MIT"
}
  </code>
</pre>



<b>How to use your project javascript library : </b>
suppose we want to use a javascipt library our project.so what we do. we can easily do this. just open your command prompt and write
javascritp library name see

<pre><code>npm install unserscore --save</code></pre>

when completely done this plugin then we can see our project directory package.json file added a new text inside the package.json file.there are a new text added like dependence and inside underscore something like this. and added root directory a folder node_modules . node_modules use my plugin which thirt party library dependenecy here are all kind of code.

when installed plugin .then where you use plugin here simply require this plugin. i want to require this package app.js file like:-

<pre>
  <code>
    var lodash = require('lodash');
    var output = lodash.without([1, 2, 3], 1);
    console.log(output);
  </code>
</pre>

if you want to show ouput you can type command prompt :-
<pre><code>node app.js</code></pre>

if you have to delete node_modules folder then your plugin dependence are not working . but package.json file already store my plugin information . so no problem but again install those plugin . so you can write simply :

<pre><code>npm install</code></pre>

<b>NPM Dependency : </b>
there are 3 kinds of dependency, but we always use two dependency.
1.dependencies
2.devDependencies
3.perDependencies

<h4>Dependencies : </h4>
when any plugin we want to enable your project still your project running. that means this pluign is mandotory to your project if you want to delete this plugin your project not working. this system is Dependencies .

<h4>devDependencies : </h4>
when any plugin just only enable your project still when you develop the project. but not necessary to production version this system is called devDependencies. like gulp, scss etc.

<b>Describe Package :</b>
you can install a package globally or locally. 
<pre><code>Global Mode :  npm install uglify-js --global</code></pre>
<pre><code>show how many package are install globally : npm list --global</code></pre>
<h5>note : when you install your package globally we can available this plugin you command prompt. </h5>

<b>package.json : </b>
we can see this file two things
1. main (this is the entry point our project) 
2. script (run the specfic package)

<b>How to uninstall local package :  </b>
you you want to uninstall your local package then you can write your command prompt

<pre><code>npm uninstall underscore</code></pre>

then you can see your package.json file you can not find the underscore package.

<b>Install a specific version : </b>
if you want to use underscore package to specific version. then we can write

<pre><code>npm install underscore@1.9.0</code></pre>

then you can check package.josn file we this specific version here.

<b>How to update package : </b>
first of all we want to check those plugin have to update version yes or not. if the version are available
then update . first check yes or no
<pre><code>npm outdated</code></pre>

if the version are available then update
<pre><code>npm update underscore</code></pre>

<b>Short Technique (Alliases) : </b>

<pre><code>npm i underscore (install local package)</code></pre>
<pre><code>npm i -g underscore (install package globally)</code></pre>
<pre><code>npm un  underscore (uninstall local package)</code></pre>
<pre><code>npm up (npm package update)</code></pre>
<pre><code>npm ls (list installed modules)</code></pre>
<pre><code>npm help (all npm command show here)</code></pre>
<pre><code>npm view underscore (details package inforamtion)</code></pre>

<h5>note : at a time we can install multiple package.</h5>
<pre><code>npm i express moment lodash mongoose</code></pre>

<b>When use --save and --save-dev :</b>
<pre><code>npm install underscore --save</code></pre>
that means this package higly depend our project. if you delete this package we will not run my project.
<pre><code>npm install underscore --save-dev</code></pre>
that means this package only enable the development part. not need to production part.


<b>Version package.json : </b>
<pre>you can see this file version text and also can see the version type like 8.9.4 that means 3 digit. </pre>
<h4>patch 4 : </h4>
<pre>patch or debugh. that means some debuging when updated change this patch version</pre>
<h4>minor 9</h4>
<pre>someting software change like api related change. then minor version change</pre>
<h4>major 8</h4>
<pre>almost hold system are change then change this version.</pre>
<h4>carrat(^)</h4>
<pre>that means when any body use the lastest minior version updated.</pre>



























































