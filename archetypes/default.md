---
title: {{ replace .Name "-" " " | title }}
subtitle: "子标题"
date: {{ .Date }}
type: posts
author: {{ .Site.Author.name  }}
#weight: 0
description: "文章摘要"
keywords: ["geekswg"] #关键词
featuredImage: "/images/posts/featured-image.jpg"
tags: ["标签1","标签2"]
categories: ["分类"]
---
!!! warning 标题
    note abstract info tip success question warning failure danger bug example quote