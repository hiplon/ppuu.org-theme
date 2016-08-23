
==============

ppuu.org-theme 一个在中国访问比较友好的 [Jekyll](http://jekyllrb.com/) 主题, 基本参考了 [wangana](https://github.com/iamnii/wangana/) 的主题并且将静态资源分别用百度CDN，又拍云，同时使用阿里的iconfont替换了fontawesome，使得在国内访问速度大大提升，

同时在原主题基础上增加了分页功能，去除了一些无关紧要的逻辑，将jquery.timeago汉化。可参考 [ 对Jekyll博客的本地化优化 ](https://ppuu.org/2016/08/optimize-and-speed-up-jekyll/)

* Demo [ppuu.org](http://ppuu.org/)

## 截图
暂无


## 安装 及 使用
1 > [下载](https://github.com/hiplon/ppuu.org-theme/archive/master.zip) 压缩包

2 > 修改 configuration file (/_config.yml) by uncommenting the differents and edit to taste
Edit: _config.yml (general options), main.css (theme colors & fonts)
``` bat
ppuu.org-theme/
├── _config.yml
├── _assets/
    ├── _scss/
        ├── main.scss
```

3 > 使用命令这些大家都会了 Run locally with the following commands while in the root directory and view in a browser at localhost:4000
``` bat
$ jekyll build
# Compile and build site files

$ jekyll serve --watch
# Serve site locally
```

## Copyright & License
The MIT License (MIT), Copyright (c) 2014 Nii Adjetey Sowah. [Read full document.](LICENSE)
