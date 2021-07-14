# webpack-bundle

1. 可通过 `SplitChunksPlugin` 实现个性打包需求 
2. 设置多个 `entry`, 将项目打包成多个文件。
   - 根据页面功能，将各个页面用到的主要库打包成一个bundle
   - 可以考虑是否能进一步将打包的bundle进行懒加载

## 参考
- [umi issues](https://github.com/umijs/umi/issues/1015) 
- [提供代码分割的最佳实践](https://github.com/frontend9/fe9-library/issues/242)
- [SplitChunksPlugin doc](https://webpack.js.org/plugins/split-chunks-plugin/)
- [entry points](https://v4.webpack.js.org/guides/output-management/)
