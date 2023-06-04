# Personal blog made with HUGO

Minimalistic blog with notes about Web made with HUGO and Github Pages.  
Forked from [Archie Theme](https://github.com/athul/archie)

## Links

URL: (https://lunkow.github.io/hugo-blog/)

## Features

- Google Analytics Script
- Callouts
- Tags
- Auto Dark Mode(based on system theme)
- Dark/Light Mode toggle
- tl:dr; frontamatter
- Cache busting for CSS files
- Disqus Comments

## Writing Posts

Create a new `.md` file in the *content/posts* folder
```yml
---
title: Title of the post
description:
date:
tldr: (optional)
draft: true/false (optional)
tags: [tag names] (optional)
---
```

## Config Options

### Custom CSS

Custom CSS files can be included though the `customcss` config parameter.  
Note: CSS files should be placed under the `assets` directory e.g. `assets/css/first.css`.

```toml
[params]
	customcss = ["css/first.css", "css/second.css"]
```

# TODO

- ~~Update Home Page content, social links~~
- ~~Set Disqurs comments~~
- Update Google Analytics
- Update posts and remove old ones