---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /index.html
header:
  image: /assets/img/DSC_1146-2.jpg
tagline: > # this means to ignore newlines until "repository:"
  Life,Nepal,Australia
excerpt: >
  Life,Nepal,Australia
repository:
  is_project_page: true
  show_downloads: true
  repository_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog
  zip_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.zip
  tar_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.tar.gz
ref: home
lang: en
---


{% include facebook-page-summary.html %}


<h2>Latest Articles</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" %}

