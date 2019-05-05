### 基础
   1、.editorconfig文件 [官网](https://editorconfig.org)
   2、eslint [官网](https://cn.eslint.org/)
   3、handlebars
   4、缓存 
      expires  cache-control
      if-modified-since / last-modified
      if-none-match /Etag
   5、cli
      安装
         npm i -g anydoor
      
      使用
         anydoor              # 把当前文件夹作为服务器根目录
         anydoor -p 8080      # 设置端口号
         anydoor -h localhost #设置host为localhost
         anydoor -d /usr      #设置根目录

      yargs
