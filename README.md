# Cavy

## Introduction

Cavy is a second-hand books trading platform application based on WeChat Platform Application

## Features

- Based on WeChat Application Platform, the current WeChatecosystem makes the application easier to use
- Mainly used MySQL and Django frame for the back end part
- Mainly used Java Script  frame for the front end part

## Structure

| Name                | Function                                             |
| ------------------- | ---------------------------------------------------- |
| images/             | images used in the application                       |
| pages/              | Animation materials used while using the application |
| utils/              | Optimize interface                                   |
| app.js              | Optimize the implementation of Interface             |
| app.json            | Update the Users' Window                             |
| app.wxss            | Update components in wxparse                         |
| project.config.json | Set configuration information                        |

## Usages

### Requirements

- You need download WeChat Development Platform to use this application
- Set packages into according placement to run the application
- Use API that WeChat Application Platform offers

### Instructions for use

- Apply for the backstage account, and get your own exclusive domain name

- Open the according trading module

- revise the project.config.json file

  ```js
  {
  	"description": "项目配置文件。",
  	"setting": {
  		"urlCheck": false,
  		"es6": true,
  		"postcss": true,
  		"minified": true,
  		"newFeature": true
  	},
  	"compileType": "miniprogram",
  	"libVersion": "1.9.91",
  	"appid": "wx176851c9e6b0327a",
  	"projectname": "tunshu",
  	"condition": {
  		"search": {
  			"current": -1,
  			"list": []
  		},
  		"conversation": {
  			"current": -1,
  			"list": []
  		},
  		"game": {
  			"currentL": -1,
  			"list": []
  		},
  		"miniprogram": {
  			"current": -1,
  			"list": []
  		}
  	}
  }
  ```

- Set a legal domain name for the application
- restart the WeChat Development Tools

## For Users you can Scan the QRcode with WeChat

![](https://github.com/ReynoldZhao/Cavy/raw/master/Cavy/cavyscancode.png)
## Here is a video presentation

![](https://github.com/ReynoldZhao/Cavy/raw/master/Cavy/Cavy.gif)
