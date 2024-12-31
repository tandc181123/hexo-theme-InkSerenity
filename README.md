# hexo-theme-InkSerenity
A simple theme

## How to Use

```
git clone https://github.com/tandc181123/hexo-theme-InkSerenity.git themes/InkSerenity
cd themes/InkSerenity
npm install
```

### Edit scaffolds/page.md
```
---
title: {{ title }}
layout: {{ title }}
current: {{ title }}
---
```

### Required Pages
The following pages need to be created manually; otherwise, the related features will not work properly:
- categories
- tags
- about

```bash
hexo new page <page-name>
```

### Utterances
This configuration is located in the *theme*’s _config.yml file.
```yml
utterances:
  repo: "<username>/<repo-name>"
  issue_term: "pathname"
  theme: "github-light"
```

### Change the theme to InkSerenity
This configuration is located in the *root* _config.yml
```yml
theme: InkSerenity
```