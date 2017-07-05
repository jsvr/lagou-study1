### 拉勾App Learning record

> [Gulp 中文网](http://www.gulpjs.com.cn/)

  + 优点
    - 基于流、任务化 
  + 常用API
    - src   (读取文件和文件夹)
    - dest  (写文件,生成文件)
    - watch (监控文件)
    - task  (定制任务)
    - pipe  (用流的方式处理文件)
  + gulp 启动任务
    ```bash
    gulp 任务名字 enter
    gulp (全部启动) enter
    ```
> 项目管理

  + 初始化项目,生成package.json文件
    ``` bash
    npm init
    ```
  + 全局安装 gulp
    ``` bash
    npm i -gulp
    ```
  + 全局安装 bower(包管理)
    ``` bash
    npm i -g bower
    ```
    
> 项目gulp插件
  
  + gulp-clean
  + gulp-concat
  + gulp-connect
  + gulp-cssmin
  + gulp-imagemin
  + gulp-less
  + gulp-load-plugins
  + gulp-uglify
  open
  
> 编写任务
  
  + lib
  + html
  + json
  + css
  + js
  + image
  + clean
  + reload
  + watch