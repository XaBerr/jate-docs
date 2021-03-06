---
title: "Html-class"
permalink: /html-class/introduction
excerpt: "html-class."
last_modified_at: 2018-08-05T16:28:04-05:00
toc: false
---

## Introduction
<figure>
	<a href="https://user-images.githubusercontent.com/16030020/44004136-93ac1c2c-9e5d-11e8-8df5-9db5f9bab7a8.png">
    <img src="https://user-images.githubusercontent.com/16030020/44004136-93ac1c2c-9e5d-11e8-8df5-9db5f9bab7a8.png">
  </a>
	<figcaption>
    Html inheriting
  </figcaption>
</figure>
The _Html_ class is the main class, all models are built inheriting from it.
The most important model is the _Template_ from which all the controllers used to render the pages will be inherited.
The _Html_ class provides methods and attributes, in particular two are the most important _init_ and _draw_.
Each controller that inherits the _Template_ will have to call up the parent's _init_ through the command `parent::init()`.

## Methods
- init
- draw
- addFiles
- addFilesRequired
- addConnection
- query
- queryFetch
- queryArray
- queryInsert

## Attributes
- template
- tags
