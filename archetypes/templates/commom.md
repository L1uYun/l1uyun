---
date: <% tp.file.creation_date("YYYY-MM-DD-HH-mm") %>
title: <% tp.file.title %>
tags:
  - <% tp.system.suggester(item => item, Object.keys(app.metadataCache.getTags()).map(x => x.replace("#", ""))) %>
---

