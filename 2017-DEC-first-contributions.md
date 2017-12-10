# Notes for first contribution project

### TODOS
- upgrade the plugins api to match changes in webpack 4.0.0-alpha.
  - where can we reference the api or find what to change?
- update the plugin documentation to for [webpack2](https://webpack.js.org/concepts/plugins/) to be as comprehensive as [webpack1](https://webpack.github.io/docs/plugins.html)

- [CONTEXT: issue - webpack 4.0.0-alpha.0 feedback](https://github.com/webpack/webpack/issues/6064)

**Related PR's**
- [feat(tapable): upgrade Single|Multi|DynamicEntryPlugin to tapable v1 #6078](https://github.com/webpack/webpack/pull/6078/files)
- [Improve `PluginEnvironment` helper to support tapable's hooks #6079](https://github.com/webpack/webpack/pull/6079)

---

### But how does it work tho...
- [Webpack's Contributing Documentation](https://github.com/webpack/webpack/blob/master/CONTRIBUTING.md)
- [VIDEO: Everything is a plugin! Mastering webpack from the inside out](https://www.youtube.com/watch?v=4tQiJaFzuJ8): this video is great and helped me understand the relevance of plugins.
  - [github: Artsy Webpack Tour](https://github.com/TheLarkInn/artsy-webpack-tour)
  - [github: Everything is a Plugin](https://github.com/TheLarkInn/everything-is-a-plugin)

- The Contributors Guide to Webpack:
  - [Part 1: A(n) (eco)system overview](https://medium.com/webpack/the-contributors-guide-to-webpack-part-1-a0410cc82ca4)
  - [Part 2: Diving Deeper: Tapable, plugins and design patterns!](https://medium.com/webpack/the-contributors-guide-to-webpack-part-2-9fd5e658e08c)
  - [Part 3: Building the Dependency Graph](https://medium.com/webpack/the-contributors-guide-to-webpack-part-3-44cc149af02c)
