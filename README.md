webpack的构建练习
此项目只是一些基础功能：
1，自动清空dist目录内容 clean-webpack-plugin 插件功能
2，自动生成index.html页面 html-webpack-plugin 插件功能
3， source-map生成打包文件后可以快速定位查询bug
4，使用webpack-dev-server插件，可以开启服务，并且修改保存代码后自动在内存中修改打包文件并且更新浏览器

使用方法：
打包文件 => 'npm run build'
开启服务开发环境 => 'npm run dev'