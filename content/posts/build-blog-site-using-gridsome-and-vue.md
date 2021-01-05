---
title: Build Blog Site using Gridsome and Vue
date: 2021-01-04
published: true
tags: ['Gridsome', 'Vue', 'Static Site Generator']
series: false
description: "In this post we will use Gridsome as static site generator tool. which is fast and easy to create blogs.
Gridsome is based on Vue Js and it is highly inspired from to Gatsby."
---
### Introduction
First of all lets understand about Gridsome.`what is Gridsome?` Grisome is [Jamstack](https://gridsome.org/docs/jamstack/) framework
to build static website and it is build on VueJs.

### How it works?
Source plugin which fetch the content from local file or get data from other API's and dump those data in local databse.
Gridsome uses [GraphQL](https://graphql.org/learn/) to fetch data which is required by VueJs componant or pages.

### Getting started
we need to install `gridsome-cli` locally or you can use `npx` to create simple blog project

if you are using npm then  `npm install -g @gridsome/cli` command or if you are using yarn then use
  `yarn global add @gridsome/cli` command to get installed `gridsome-cli`

or simply use npx to create simple project
```
  npx gridsome create 'simple-blog-project'
  cd simple-blog-project
  npm install
```

### Directory Structure and files
- `package.json` this file content the packages or plugins which have been used in project.
- `static`  Files which will be put inside this folder will be copied to `dist` directory after project build.

