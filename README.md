# blog

### 准备工作
1. 安装visual studio code

    [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. 安装适合github的markdown插件

    [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
3. 安装git客户端

    [https://git-scm.com/](https://git-scm.com/)
4. 安装nodejs

    [https://nodejs.org/zh-cn/](https://nodejs.org/zh-cn/)
5. markdown语法学习

    [维基百科](https://zh.wikipedia.org/wiki/Markdown)  
    [Markdown 新手指南](http://www.jianshu.com/p/q81RER)  
    [Markdown指南](https://www.binarization.com/archive/2016/markdown-guide/)

### 发布运行
1. 安装依赖包文件
```
npm install
```
2. 新建文章
```
hexo new '文件名'
```
3. 清除缓存（非必需）
```
hexo clean
```
4. 生成静态文件
```
hexo generate 

hexo g //简写
```
5. 压缩js和css（非必需）
```
npm run gulp
```
6. 发布
```
hexo deploy

hexo d //简写
```
