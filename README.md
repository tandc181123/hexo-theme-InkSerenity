# hexo-theme-InkSerenity
**A simple and elegant theme for Hexo.**

## Installation Guide
### 1. Download the Theme
Clone the theme repository into your Hexo project's `themes` folder:
```
git clone https://github.com/tandc181123/hexo-theme-InkSerenity.git themes/InkSerenity
cd themes/InkSerenity
npm install
```

### 2. Update Hexo Scaffolds
Modify the default `scaffolds/page.md` file to include required metadata:
```
---
title: {{ title }}
layout: {{ title }}
current: {{ title }}
---
```

### 3. Create Required Pages
Manually create the following pages for all features to function properly:
- **Categories**
- **Tags**
- **About**

Run the following command for each page:
```bash
hexo new page <page-name>
```
Example for creating the categories page:
```bash
hexo new page categories
```

### 4. Apply the InkSerenity Theme
In the root `_config.yml` file of your Hexo project, update the `theme` setting:
```yml
theme: InkSerenity
```
### Optional Configurations
#### Utterances (Commenting System)
To enable **Utterances**, configure it in the theme's `_config.yml` file:
```yml
utterances:
  repo: "<username>/<repo-name>" # Replace with your Github repository
  issue_term: "pathname"
  theme: "github-light"
```
>**Note**: Utterances requires a valid Github repository to store comments.
### Google Analytics
To enable **Google Analytics**, configure your tracking ID in the theme's `_config.yml` file:
```yml
google_analytics: 
G-XXXXXXXXXX # Replace with your tracking ID
```