+++
title = "{{ humanize .Name | title }}"
authors = [{{ .Params.author | default .Site.Author.name }}]
description = ""
Summary = ""
date = {{ .Date }}
slug = "{{ urlize .Name }}"
categories = []
series = []
tags = []
math = "KaTeX"
draft = true
featured = false
+++
