---
title: About
date: 2023-11-05T15:39:43-05:00
draft: false
hide_footer: true
---

<h2>About Me:</h2>
I'm learning Hugo, one step at a time.
<p>A Go template is a normal HTML page. When you want to execute a piece of code,<br />you can use double curly braces like this: {{ "Hello!" }}.</p>

<!-- Sometimes you'll want to set a variable globally in your config.toml. 
Hugo has already initalized a title in your config.toml. You can access
a variable from your global config with site. For example: -->

<title>{{ .Params.title }} | {{ .Site.title }}</title>

{{ $favorite_food := "Gazelle" }}
{{ $favorite_food }}