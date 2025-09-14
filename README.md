A Death Note theme for jekyll.

[Preview](https://startracex.github.io/dn/)

I've tried to use fonts similar to those in Death Note. The accessibility of this theme is very low.

Add theme to remote theme in `_config.yml`:

```yml
remote_theme: startracex/dn
plugins:
  - jekyll-remote-theme
```

Add a `notes` collection in `_config.yml`:

```yml
collections:
  notes:
    output: true
    permalink: /notes/:name
```

Write content in `_notes` folder, add `layout: note` in front matter.

`_notes/how-to-use-it.md`:

```md
---
layout: note
title: "How to use it"
---

## Entering Names

The human whose name is written in this note shall die. This note will not take effect unless the writer has the subject's face in mind when writing his/her name. This is to prevent people who share the same name from being affected.
```
