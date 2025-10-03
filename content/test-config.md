---
title: '配置测试页面'
date: 2024-01-01T00:00:00+08:00
draft: false
---

## 配置值测试

- **Site.Params.name**: {{ .Site.Params.name }}
- **Site.Params.author**: {{ .Site.Params.author }}  
- **Site.Params.avatar**: {{ .Site.Params.avatar }}
- **Site.Title**: {{ .Site.Title }}
- **Site.Author**: {{ .Site.Author }}

## 所有Params
{{ range \, \ := .Site.Params }}
- **{{ \ }}**: {{ \ }}
{{ end }}
