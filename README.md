### 生产环境配置说明
---
1. gulp配置说明

|命令|说明|依赖|
|---|:---:|---|
| gulp| 启动serve并监听| serve|
| serve | 启动serve并监听| build|
| build| 构建项目| lib,js,image,less,html,json |
| clean| 清空devPath,prdPath路径下文件| null |

2. 启动项目
	- 全局安装gulp
	- <pre>cnpm i --save-dev gulp-clean gulp-concat gulp-connect gulp-cssmin gulp-imagemin gulp-less gulp-load-plugins gulp-uglify open<pre>
	
	
---
