# Notes for first contribution project

Our first project is to upgrade the plugins to the new webpack 4.0.0-alpha.

- [CONTEXT: issue - webpack 4.0.0-alpha.0 feedback](https://github.com/webpack/webpack/issues/6064)

**QUESTIONS FOR SEAN**
- You mentioned we needed to update the plugins to match the 4.0-alpha api: where can we reference the api?

**Related PR's**
- [feat(tapable): upgrade Single|Multi|DynamicEntryPlugin to tapable v1 #6078](https://github.com/webpack/webpack/pull/6078/files)
- [Improve `PluginEnvironment` helper to support tapable's hooks #6079](https://github.com/webpack/webpack/pull/6079)

---

**Foundational Education**
- [Webpack's Contributing Documentation](https://github.com/webpack/webpack/blob/master/CONTRIBUTING.md)
- [VIDEO: Everything is a plugin! Mastering webpack from the inside out](https://www.youtube.com/watch?v=4tQiJaFzuJ8): this video is really great and helped me understand the plugin system that we're working on.
  - [github: Artsy Webpack Tour](https://github.com/TheLarkInn/artsy-webpack-tour)
  - [github: Everything is a Plugin](https://github.com/TheLarkInn/everything-is-a-plugin)
The Contributors Guide to Webpack:
- [Part 1: A(n) (eco)system overview](https://medium.com/webpack/the-contributors-guide-to-webpack-part-1-a0410cc82ca4)
- [Part 2: Diving Deeper: Tapable, plugins and design patterns!](https://medium.com/webpack/the-contributors-guide-to-webpack-part-2-9fd5e658e08c)
- [Part 3: Building the Dependency Graph](https://medium.com/webpack/the-contributors-guide-to-webpack-part-3-44cc149af02c)
