---
layout: post
title: "Setting up Jekyll on Mac OS"
date: 2017-08-28
---

Ensure you have hombrew installed. We will need RubyGems (gem) package manager to install Jekyll.

To install gem:
```
brew install ruby
```

Install Jekyll following that by:
```
sudo gem install jekyll
```

To confirm installation, check the version:
```
jekyll -v
```

To start a Jekyll pased project, inside the project directory run:
```
jekyll serve
```