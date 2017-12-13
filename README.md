# LG Webpack Contribution Guide
A (WIP) guide for first time contributors to the webpack ecosystem.




## Generally Contributing to Opensource
Generally, contributing to opensource for the first time can be overwhealming! Don't panic. It's ok, we're here for you. 
- [First Timers Only](http://www.firsttimersonly.com/)
- Open Source Guides: [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- Free Code Camp: [How to Contribute to Open Source](https://github.com/freeCodeCamp/how-to-contribute-to-open-source)




## WEBPACK ISSUES
- [D0 - 1st Contribution](https://github.com/webpack/webpack/issues?q=is%3Aissue+is%3Aopen+label%3A%22D0%3A+My+First+Commit+%28Contrib.+Difficulty%29%22)
- [D1 - Easy Difficulty](https://github.com/webpack/webpack/issues?q=is%3Aissue+is%3Aopen+label%3A%22D1%3A+Easy+%28Contrib.+Difficulty%29%22)
- [X5 - Work Required/ Help Needed](https://github.com/webpack/webpack/labels/X5%3A%20work%20required%20%28PR%20%2F%20Help%20Wanted%29)




## LG TODOS
- upgrade the plugins api to match changes in webpack 4.0.0-alpha.
  - where can we reference the api or find what to change?
- update the plugin documentation to for [webpack2](https://webpack.js.org/concepts/plugins/) to be as comprehensive as [webpack1](https://webpack.github.io/docs/plugins.html)
- Get webpack on [Up-For-Grabs.net](http://up-for-grabs.net/#/)
- [CONTEXT: issue - webpack 4.0.0-alpha.0 feedback](https://github.com/webpack/webpack/issues/6064)

**Related PR's**
- [feat(tapable): upgrade Single|Multi|DynamicEntryPlugin to tapable v1 #6078](https://github.com/webpack/webpack/pull/6078/files)
- [Improve `PluginEnvironment` helper to support tapable's hooks #6079](https://github.com/webpack/webpack/pull/6079)




## WEBPACK: UNDER THE HOOD
### But how does it work tho...
- [Webpack's Contributing Documentation](https://github.com/webpack/webpack/blob/master/CONTRIBUTING.md)
- ARTICLE: The Contributors Guide to Webpack:
  - Part 1: [A(n) (eco)system overview](https://medium.com/webpack/the-contributors-guide-to-webpack-part-1-a0410cc82ca4)
  - Part 2: [Diving Deeper: Tapable, plugins and design patterns!](https://medium.com/webpack/the-contributors-guide-to-webpack-part-2-9fd5e658e08c)
  - Part 3: [Building the Dependency Graph](https://medium.com/webpack/the-contributors-guide-to-webpack-part-3-44cc149af02c)
- VIDEO: [Everything is a plugin! Mastering webpack from the inside out](https://www.youtube.com/watch?v=4tQiJaFzuJ8): this video is great and helped me understand the relevance of plugins. Links mentioned in the talk:
  - [github: Artsy Webpack Tour](https://github.com/TheLarkInn/artsy-webpack-tour)
  - [github: Everything is a Plugin](https://github.com/TheLarkInn/everything-is-a-plugin)
- VIDEO: [Sean's Twitch stream from 10/9](https://www.twitch.tv/videos/208289699) where he goes over how webpack works and makes contributions.
- ARTICLE: [The new plugin system (week 22–23)](https://medium.com/webpack/the-new-plugin-system-week-22-23-c24e3b22e95)
- VIDEO: [From start to finish: A 20-ish minute contribution to webpack](https://www.youtube.com/watch?v=ePdXHF2DfeY&feature=youtu.be)

#### relevant sub libraries
- [tappable](https://github.com/webpack/tapable)
