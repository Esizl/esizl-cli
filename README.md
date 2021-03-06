 # esizlcli
 
 > A CLI tool to create template files for all languages and frameworks.

[![npm version](https://img.shields.io/npm/v/esizlcli.svg?style=flat-square)](https://www.npmjs.org/package/esizlcli)
[![install size](https://packagephobia.now.sh/badge?p=esizlcli)](https://packagephobia.now.sh/result?p=esizlcli)
[![Support Server](https://img.shields.io/discord/520075719603257345.svg?color=7289da&logo=discord&style=flat-square)](https://discord.gg/vqBE6xE)
<!--- [![npm downloads](https://img.shields.io/npm/dt/esizlcli.svg?style=flat-square)](http://npm-stat.com/charts.html?package=esizlcli) -->

 ## Installation

 Install and access anywhere.
 
 ```
 npm i esizlcli -g
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
