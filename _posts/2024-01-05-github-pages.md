---
layout: default
permalink: ghp
---

# host a free static html blog on github pages

## table of contents 

- why you even should
- 
- step one:
- step two:
- step three:
- step four:
- step five:

---

## readme

this tutorial assumes a very basic understanding of html. you don't actually need to know html, you just need to be able to interpret it, ask google smart questions, rework it, and copy and paste. still, I recommend you invest
some time in learning it more thoroughly and understanding some of the more advanced things you can do on github pages that will make your life as webmaster easier.

---

## why you even should

---

## step one: create your github account and base site repository

create a github account and create a new repository. call this repository <code>username.github.io</code>. don't call it anything else. this will allow you to host a website at http://username.github.io. don't worry, you
can change the url later. subsquent repositories can be named whatever you like and can be found as part of your website at http://username.github.io/whateveryouwanttoputhere. for example, a repository
called <code>lloyd-christmas</code> could be hosted online at http://username.github.io/lloyd-christmas.

---

## create your site homepage

create a new file called <code>index.html.</code> this will be your homepage hosted at http://username.github.io/. leave everything else blank but enter the following...

<pre>
---
layout: default
---
</pre>

that's it. save it. 

---

## create your layout template and style it

create a new file called <code>/_layouts/default.html</code>. put the following code into the file and save.

```
<html>
<body>
<head>
<style>
</style>
</head>
<main>
{{content}}
</main>
</body>
</htmL>

```

