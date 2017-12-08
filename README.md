# webpack

1.使用前需要安装webpack

(1)全局安装：npm install -g webpack

(2)当前目录安装：npm install --save-dev webpack

2.使用babel必须安装的几个包

npm install babel-core babel-loader babel-preset-es2015(注意npm版本) babel-preset-react --save-dev

3.js文件打包

npm install html-webpack-plugin --save-dev

4.css文件打包

npm install extract-text-webpack-plugin --save-dev

5.图片打包及路径配置

npm install style-loader css-loader file-loader url-loader --save-dev

*问题：css中background属性图片路径存在问题，尚未解决
