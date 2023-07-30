# Source files for CSSB official documentation website 

URL : https://infos.cssb.fr/

Web content is written in .md files. After committing the changes on the `gaia` branch, Jekyll is executed on them to generate .html files, and the website is automatically updated.

Website uses [Jekyll](https://jekyllrb.com/) with the [Odin template](https://github.com/TeaGuns/odin) for knowledgebases and support sites. Please see the [official Jekyll docs](https://jekyllrb.com/docs/) for more info on running, building and editing a Jekyll site.

## Local developments

The website is in current development : more examples, tutorials, ... are continuously added and improved.
Any contribution through a pull request from any fork is welcomed.

In order to generate the website locally (for tests), you need the ruby packages `jekyll` and `bundle` installed on your computer. See https://jekyllrb.com/docs/ for more details.

Then installed all the website dependencies using

```bash
bundle install
```

and generate the website using

```bash
bundle exec jekyll serve --livereload
```

Then you can browse the website at this address : http://127.0.0.1:4000/infos/.
The `--livereload` option allows to update the website rendering every time you modify a local source file.

# Modifications

### Icons
Icons are from [Iconscout](https://iconscout.com/unicons/explore/line)

### Adding a category
To add a category or a subcategory, you need to add a folder in the directory of your choice. The name of the folder will be the name displayed in the URL. In this folder, you need to add a file named `index.html` with the following content :

```markdown
---
layout: category
title: CATEGORY_NAME
description: General description of the category
icon: Ex: uil-cog (see https://iconscout.com/unicons/explore/line)
---

{% include category-display.html %}
```

### Adding a page

To add a page, you need to add a file in the directory of your choice. The name of the file will be the name displayed in the URL. In this file, you need to add the following content :

```markdown
---
layout: post
title: "PAGE_NAME"
rank: Ex: 4 (the lower the number, the higher the page will be displayed in the menu)
summary: "Résumé en une phrase courte du contenu de la page" 
---

:scroll: _Description rapide des informations présentes dans la page (facultative)_

- [Première Section](#première-section)
- [Deuxième Section](#deuxième-section)

## Première Section

Contenu ...

## Deuxième Section

Contenu
```
