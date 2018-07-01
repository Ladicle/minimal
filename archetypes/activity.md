---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
link: "/activity/{{ .TranslationBaseName }}"
activityType: "speak"
date: {{ dateFormat "2006-01-02" .Date }}
lang: "jp"
categories: ["event"]
tags: []
---
