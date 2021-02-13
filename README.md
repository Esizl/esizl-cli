 # esizl-cli
 
 > A CLI tool to create template files for all languages and frameworks.

[![npm version](https://img.shields.io/npm/v/esizl-cli.svg?style=flat-square)](https://www.npmjs.org/package/esizl-cli)
[![install size](https://packagephobia.now.sh/badge?p=esizl-cli)](https://packagephobia.now.sh/result?p=esizl-cli)
[![npm downloads](https://img.shields.io/npm/dt/esizl-cli.svg?style=flat-square)](http://npm-stat.com/charts.html?package=esizl-cli)


 ## Installation

 Install and access anywhere.
 
 ```
 npm i esizl-cli -g
 ```
 
## Help

For Help use this command
```
emit --help
```
or 
```
emit -h
```

 ## Usage

* __To generate a simple file, use the following command.__
 
 ```
 emit <filetype> <filename> 
 ```
 
 > Note: This command can & will overwrite existing files.

 For Example:

 Generate a file  `Cool.html` with:
 
 ```
 emit html Cool
 ```

 > Note : default name is ```Index```  

 * __To Generate a file for a framework.__

 ```
 emit <filetype> <filename> <framework> 
 ```

 For Example:

 Generate a file  `Header.js` for react framework with:
 
 ```
 emit js Header --rafc
 ```

 > Note: Frameworks command is additionally designed for frameworks.

## Contribution

- Pull Requests are accepted.

 ## License
 
 > ISC License