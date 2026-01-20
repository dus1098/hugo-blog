+++
title = "{{ replace .File.ContentBaseName "-" " " | title }}"
date = {{ .Date }}
draft = true
slug = "{{ .File.ContentBaseName }}"
uid = "{{ now.Unix }}"
tags = []
categories = []
summary = ""
+++