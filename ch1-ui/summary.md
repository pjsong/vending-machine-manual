# 第一章 界面

## 项目文件
###插件
#####loader plugin
    
1. raw-loader: webpack插件，将文件作为字符串引入。
2. sass-loader: 装入并编译SASS/SCSS为css，依赖tools plugin 2
3. css-loader: css翻译为CommonJS
4. style-loader: 为JS字符串创建style节点
5. 用raw-loader ~~html-loader: HTML输出为字符串, 根据编译需要进行压缩~~
6. ts-loader: webpack的typescript装入器
7. file-loader: 文件处理，输出到output目录
8. url-loader: 功能类似file-loader. 小于指定大小的文件可以返回data URL如data:xxxxx, 否则用file-loader处理
9. angular-router-loader: 让Angular Router支持基于字符串的模块装入
10. angular2-template-loader: 在component.ts组件中引入templateUrl,styleUrl时省略require.
10. font-awesome: 图标字体/css工具包
11. bootstrap-sass: sass版本的bs3
    
#####Tools plugin
1. ExtractTextPlugin: 将CommonJS中的css模块提取为独立的文件
2. node-sass: Nodejs下的libSass实现,实现scss文件的原生编译
3. jasmine-core: js的行为驱动开发(BehaviorDrivenDevelopment)测试框架
4. HtmlWebpackPlugin: 为html自动插入script, link之类的tag
5. LoaderOptionsPlugins: 重载loader选项
6. DefinePlugin应用的环境变量
7. CommonsChunkPlugin： 分离第三方js和app, app->vendor->polyfills遇到相同的依赖,从前面的开始移除
8. ContextReplacementPlugin: context是指require带表达式如 <code>require('./locale/' + name + '.json') </code>， 当webpack遇到这样的表达式,因为编译时name未知, 会在bundle中把每个文件都作为模块包含进来。本插件可以过滤包含进来的模块。[webpack说明](https://webpack.js.org/plugins/context-replacement-plugin/), [github来源](https://github.com/angular/angular/issues/11580)
## 操控界面
准备中

## 手机监控界面
准备中

