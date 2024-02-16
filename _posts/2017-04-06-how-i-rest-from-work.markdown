---
layout: post
title: Github Pages
date: 2024-02-16 15:50:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: software.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Holidays, Hawaii]
---

## Git Pages 만들기
 먼저이름을 일치
![I and My friends]({{site.baseurl}}/assets/img/github-page-create.jpg)


index를 만들고 github에 올리기
({{site.baseurl}}/assets/img/github-page-index.jpg)


## Jekyll 설치

Ruby 설치 후 Gem을 이용해 Jekyll을 설치


```
gem instal bundler
gem install github-pages

# windows
gem install jekyll

# macos
sudo gem install -n /usr/local/bin jekyll
```


## Jekyll 테마 입히기
[Jekyll 테마](https://jekyllthemes.io/theme/flexible-jekyll/){:target="_blank"}


다운로드후 폴더로 가져옴
({{site.baseurl}}/assets/img/Jekyll-folder.jpg)

_config.yml에서 url 추가
({{site.baseurl}}/assets/img/Jekyll-config.jpg)

## 게시글 작성하기
게시글은 _posts 경로에 작성한다
