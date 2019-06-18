# Imageiry.com API 🍅

## Overview
**Imageiry** is free and open source product that allows to create image from `html` design.
*You can use imageiry to : *

 - Turn your HTML Design into image.
 - When you use Open Graph tags to attach rich photos, you need an image, and ideally, an image based on your content
 - Enahnce the outfit for sharble content ( *With createing unquie meta image for each artical or blog* )


## Usage

Imageiry has an direct api to convert any HTML based design into image 
`http://www.imageiry.com/convert`  [**POST]**

Field | Description
------|------------
html | _Any html content_
_Note_: Imageiry will convert the _body_ of the page only.

![image](https://i.ibb.co/RDV768h/image.png)
## Ready made templates.
**Movies**
Using dynamic images for your content enrich your website and ideally enhance your user experience especially for sharable content.
*Example*:
![Default template](http://www.imageiry.com/api/movie?title=How%20to%20be%20awesome&description=be%20like%20man&moreInfo=This%20is%20more%20info%20about%20the%20link&rate=3&tag=PG-13)

_API_ `http://www.imageiry.com/api/movie` **[GET]**

Paramter | state 
------|------------
title | _required_
description | _required_
moreInfo | _required_
rate | _required_
tag | _required_
likes | _optional_
backgroundImage | _optional_
posterImage| _optional_

 

**Sample**: 
    http://www.imageiry.com/api/movie?title=How%20to%20be%20awesome&description=be%20like%20man&moreInfo=This%20is%20more%20info%20about%20the%20link&rate=3&tag=PG-13

