 ##### 将eslint的一些常用配置都装进一个包，避免每次搭建项目需要逐个引入

**下面是整合到这里面的包**

*   @babel/eslint-parser
*   @typescript-eslint/parser
*   @typescript-eslint/eslint-plugin
*   eslint-plugin-react
*   eslint-plugin-react-hooks
*   eslint-plugin-lodash
*   typescript

上面的这些包可以不用再另外安装到项目中，但是像eslint或者eslint-webpack-plugin这类插件还是必须要安装到项目。