# Saka

> An inkpaper theme based on offical theme.

## 说明

基于`ink_Werttin`修改。当修改到跟`ink_Werttin`没有关系之后我会删掉这行。

#### 预览

#### 准备食材

#### 如何食用

下载Source，把Saka文件夹放入blog目录。

修改 `config.yml` 中`site:theme`字段与`build:copy`字段如下：

```
site:
    ...
    theme: Saka
    ...
build:
    ...
    copy:
        - Saka/css
        - Saka/js
        - Saka/favicon.ico
        - Saka/robots.txt
        - source/images
    ...
``` 

