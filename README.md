# Material Flow (Modified by Ayaka Neko)

__由于本人将博客系统转到 hugo 上，本 Hexo 主题将只进行 bug 修复__   
安利一发我为 hugo 写的相同风格的主题： [YAMT](https://github.com/stkevintan/sfork)

Yet Another Material-Design-Style Hexo Theme. Demo: [https://neko.ayaka.moe/](https://neko.ayaka.moe/diary)  

![](https://i.imgur.com/l86IfdO.png)

## Installation
```bash
# change to work dir
cd /your_blog_dir/
# install dependencies
npm i -S hexo-generator-search hexo-generator-feed hexo-renderer-less hexo-autoprefixer hexo-generator-json-content
# download source
git clone https://github.com/nekomeowww/hexo-theme-material-flow themes/material-flow
git clone https://github.com/nekomeowww/hexo-global-license.git node_modules/hexo-global-license
```

## Configuration
1. Change the value of `theme` to `material-flow` in `_config.yml`.
2. Put your avatar && favicon  images to `source/images/`.
3. Edit `_config.yml` and `themes/material-flow/_config.yml` for your needs.

# License for Posts
Add these lines to your `_config.yml`:
```
licenseType: by-nc-sa #Specify the type of Creative Commons license, or custom
  #Options:
  #by: #CC Attribution
  #by-nd: #CC Attribution-NoDerivatives
  #by-sa: #CC Attribution-ShareAlike
  #by-nc: #CC Attribution-NonCommercial
  #by-nc-nd: #CC Attribution-NonCommercial-NoDerivatives
  #by-nc-sa: #CC Attribution-NonCommercial-ShareAlike
  #custom: #Specify your own custom license HTML

# licenseIconSize: normal #Specify the size of the Creative Commons image
  #Options:
  #normal
  #small
```

# What has been enhanced?

- Added the line for "© 2016 - 2017 `author name`"
- Added the Creative Common License declaration under each post
![](https://i.imgur.com/KfxNP15.png)
- Fixed the problem where the pages were being generated from `article.ejs` which will result in pages has the license declaration
- Changed some color settings

# More feature
Currently I just modified the text values directly, so there is no localization. If you want just post a issue in the issue tab and I will review it.


## More
Please refer to offical doc : <https://hexo.io/docs/index.html>
