<b>NPM</b>
the full meaning of npm -> node package manager. there are all word have a meaning. bellow all are describe : in  other word npm is the world's largest Software Registry. 

<b>Node : </b>
that means there are a lot of code like javascript.

<b>Package : </b>
when one or more javascript are boundle in one thing that called package. that means if you want to a javascritp plugin then you create a
seperate seperate file to easy way to handle your project. then your project is completed then you can boundle this seperate seperate file
in one folder that called a package.

<b>Manager : </b>
manager means node and package maintaining work.

<b> Why Node Package Manager : </b>
once upon a time javascritp only work in browser, but this time we can run this our local computer machine . this only can possible if you install your computer node.js software . by the way npm is the default tools in node js . suppose node js is the code editor and npm is the extra feature this feature easy way to code run . that means npm is a tools that way we can easy way to run code and install package. the npm most extra feature is
many other developer to develop many kind of program for other develop to develop their own application. so we can easily use this code.

<b>Project Setup : </b>
ok ! now we create a project . fist of all go the desktop and create a folder and folder name is suppose myproject. then we want to initalise your node js. so we can write our command prompt

<li>npm inti</li>
when you type this command then we can see the command put to some information. it easy. if you avoaid this process information and set
default normal information then you can write our command prompt 

<li>npm init -y </li>
y stand for yes . then we see our project directory a file this name package.json. i will disscuse later this file.

<b>How to use your project javascript library : </b>
suppose we want to use a javascipt library our project.so what we do. we can easily do this. just open your command prompt and write
javascritp library name see

<li>npm install unserscore --save</li>
when completely done this plugin then we can see our project directory package.json file added a new text inside the package.json file.there are a new text added like dependence and inside underscore something like this. and added root directory a folder node_modules . node_modules use my plugin which thirt party library dependenecy here are all kind of code.

when install plugin .then where you use plugin here simply import this plugin.  if you have to delete node_modules folder then your plugin dependence are not working . but package.json file already store my plugin information . so no problem but again install those plugin . so you write simply :

<li>npm install</li>

<b>NPM Dependency : </b>
there are 3 kinds of dependency, but we always use two dependency.
1. dependencies
2.devDependencies
3.perDependencies

<h4>Dependencies : </h4>
when any plugin we want to enable your project still your project running. that means this pluign is mandotory to your project if you want to delete this plugin your project not working. this system is Dependencies .

<h4>devDependencies : </h4>
when any plugin just only enable your project still when you develop the project. but not necessary to production version this system is called devDependencies. like gulp, scss etc.

<b>Describe Package :</b>
you can install a package globally or locally. 
<li>Global Mode :  npm install uglify-js --global</li>
<li>show how many package are install globally : npm list --global</li>
<h5>note : when you install your package globally we can available this plugin you command prompt. </h5>

<b>package.json : </b>
we can see this file two things
1. main (this is the entry point our project) 
2. script (run the specfic package)

<b>How to uninstall local package :  </b>
you you want to uninstall your local package then you can write your command prompt
<li>npm uninstall underscore</li>
then you can see your package.json file you can not find the underscore package.

<b>Install a specific version : </b>
if you want to use underscore package to specific version. then we can write
<li>npm install underscore@1.9.0</li>
then you can check package.josn file we this specific version here.

<b>How to update package : </b>
first of all we want to check those plugin have to update version yes or not. if the version are available
then update . first check yes or no
<li>npm outdated</li>

if the version are available then update
<li>npm update underscore</li>

<b>Short Technique (Alliases) : </b>
<li>npm i underscore (install local package)</li>
<li>npm i -g underscore (install package globally)</li>
<li>npm un  underscore (uninstall local package)</li>
<li>npm up (npm package update)</li>
<li>npm ls (list installed modules)</li>
<li>npm help (all npm command show here)</li>
<li>npm view underscore (details package inforamtion)</li>

<h5>note : at a time we can install multiple package.</h5>
<li>npm i express moment lodash mongoose</li>

<b>When use --save and --save-dev :</b>
<li>npm install underscore --save</li>
that means this package higly depend our project. if you delete this package we will not run my project.
<li>npm install underscore --save-dev</li>
that means this package only enable the development part. not need to production part.


<b>Version package.json : </b>
you can see this file version text and also can see the version type like 8.9.4 that means 3 digit. 

<h5>patch 4 : </h5>
patch or debugh. that means some debuging when updated change this patch version

<h5>minor 9</h5>
someting software change like api related change. then minor version change

<h5>major 8</h5>
almost hold system are change then change this version.

<h5>carrat(^)</h5>
that means when any body use the lastest minior version updated.




























































