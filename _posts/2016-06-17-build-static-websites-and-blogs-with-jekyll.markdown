---
layout: post
title:  "Build static websites and blog with Jekyll!"
categories: web
---

## Introduction

I build this blog with [Jekyll][jekyll]. It strong and useful if:

* Simple: Get up and running in few seconds.
* Static: No more databases required.
* Awesome: [Jekyll][jekyll] support [Markdown syntax][Markdown], so you can write a post as a text file, not html file.
* GitHub Page compatible: github page it free and useful, but it is not support dynamic websites with database. In this case, Jekyll is a good choice.

## Building Jekyll for Window
It is a note for me. I am using Window 10, so there are some steps to take.

#### Installation

Full guide [here](https://jekyllrb.com/docs/windows/#installation)

1. Install a package manager for Windows called [Chocolatey](https://chocolatey.org/install)
	* To install chocolatey, open an **administrative command prompt** (cmd) and run command:
``@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin``
2. Install Ruby via Chocolatey: `choco install ruby -y`
3. Reopen a command prompt and install Jekyll: `gem install jekyll`

#### Location in my PC

By default, these pakages will be installed:

* Chocolatey: `C:\ProgramData\chocolatey`
* Ruby: `C:\tools\ruby23`
* Jekyll: `C:\tools\ruby23\lib\ruby\gems\2.3.0\gems`

## Some usefull link

* [Markdown syntax][Markdown]

## References

* Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. 
* File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. 
* If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[jekyll]: https://jekyllrb.com/
[Markdown]: https://daringfireball.net/projects/markdown/