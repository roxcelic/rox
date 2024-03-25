---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'copy if youd like'
pubDate: 2024.25.03
desc: 'this is so anyone can make a site like mine in html'
author: 'roxanne angel-grist'
credits: 
---

if for any random and unknown reason you would like to make a copy of my website, go ahead I dont mine as long as you credit me and the people i credit.
you can download my base html templete here or see the code in the index.html page if youd like :)

download [gift.zip](../../gift.zip)

although this version may be getting updated less it should still be semi useable in any state and as long as you know how to use a computer
im pretty sure you could figure it out

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
		<meta name="description" content="for your entertainment and my html" />
		<meta name="viewport" content="width=device-width" />
		<link rel="icon" type="image/x-icon" href="https://avatars.githubusercontent.com/u/157179472?v=4">
		<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
		<link rel="stylesheet" href="base.css"/>
		<link rel="stylesheet" href="style.css"/>
		<link rel="stylesheet" href="media.css"/>
		<title>title goes here</title>
    </head>

    <body>
		<div class="box">
			<div class="bar">
				<marquee>
					<div class="text">
						title goes here also
					</div>
				</marquee>
			</div>
		</div>

        <div class="dropdown-box">
	    <div class="dropdown-view">
		    <div class="end2" onclick="getclickedboi('dropdown')">
			    <span class="material-symbols-outlined md">menu</span>
		    </div>

		    <div class="box">
			    <a href="/"><h1>home</h1></a>
			    <div class="vertical-row"></div><a href="/blog/"><h1>blog</h1></a>
			    <div class="vertical-row"></div><a href="/projects/"><h1>projects</h1></a>
			    <div class="vertical-row"></div><a href="/roxie/"><h1>roxie!</h1></a>
		    </div>
	    </div>
	    <div class="dropdown-content" id="dropdown">
            <h2>drop down content yayyyyyyyy</h2>
	    </div>
    </div>

    <div class="mainBox" id="mainBox">
		<div class="pictureBox"></div>
			<a href="https://github.com/roxcelic">
				<div class="roundThing"></div>
			</a>
		<h2>and now you can put whatever content you would like here, enjoy!</h2>
    </div>

	<script>
		function item_hover(description, ids) {
    		document.getElementById(ids).innerHTML = description;
		}

		function getclickedboi(id){
    		let cu = document.getElementById(id);
    		console.log(cu.style.height);
    		if (cu.style.height){
        		console.log("hey");
        		cu.style.height = ("");
    		}
    		else{
        		if(!cu.style.height){
            		console.log("bye");
            		console.log(cu.scrollHeight,"px");
            		cu.style.height = (cu.scrollHeight + "px");
        		}
    		}
		}
	</script>
</html>
```