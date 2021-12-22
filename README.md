Webpack4 Config "postcss-loader" "nesting" plugin Demo
======================================

支持webpack4的postcss-loader + postcss-nesting插件的配置。

有很多版本的坑，需要注意：
1. `postcss-loader`必须为支持webpack4的`4.x`，当前为`4.3.0`
2. postcss-loader v4后必须手动指定`css-loader`，且为支持webpack4的版本`5.x`
3. `style-loader`必须为支持webpack4的最后一个版本`1.3.0`
4. postcss相关的，只要使用postcss8，其它的插件基本上都支持它了
5. `postcss-nesting`与`postcss-nested`的区别是，语法有所不同，前面必须加`&`

```
npm install
npm run demo
```
