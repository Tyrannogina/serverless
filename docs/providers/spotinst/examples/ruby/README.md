<!--
title: Hello World Ruby Example
menuText: Hello World Ruby Example
description: Create a Ruby Hello World function
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/spotinst/)
<!-- DOCS-SITE-LINK:END -->

# Hello World Ruby Example

Make sure `serverless` is installed.

## 1. Create a service
`serverless create --template spotinst-ruby --path serviceName`  `serviceName` is going to be a new directory there the Ruby template will be loaded. Once the download is complete change into that directory. Next you will need to install the Spotinst Serverless Functions plugin by running `npm install` in the root directory. You will need to go into the serverless.yml file and add in the environment variable that you want to deploy into.


## 2. Deploy
```bash
 serverless deploy
```  

## 3. Invoke deployed function
```bash
serverless invoke --function hello
```

In your terminal window you should see the response

```bash
'{"hello":"from Ruby2.4.1 function"}'
```

Congrats you have deployed and ran your Hello World function!

## Short Hand Guide

`sls` is short hand for serverless cli commands

`-f` is short hand for `--function`

`-t` is short hand for `--template`

`-p` is short hang for `--path`
