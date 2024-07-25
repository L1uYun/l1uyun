---
date: <% tp.file.creation_date("YYYY-MM-DD-HH-mm") %>
title: <% tp.file.title %>
tags:
  - <% tp.system.suggester(item => item, Object.keys(app.metadataCache.getTags()).map(x => x.replace("#", ""))) %>
created: 2024-07-09T16:26
updated: 2024-07-18T11:45
---

