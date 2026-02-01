+++
title = "{{ replace .File.ContentBaseName "-" " " | title }}"
date = {{ .Date }}
draft = true
categories = []
tags = []
summary = ""
slug = "{{ .File.ContentBaseName }}"
uid = "{{ now.Unix }}"
+++