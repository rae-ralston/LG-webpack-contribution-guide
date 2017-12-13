# LG Webpack Contribution Guide
A (WIP) guide for first time contributors to the webpack ecosystem.



You too can start contributing to open source in just a few easy steps...
1. Familiarize yourself generally with contributing to Open Source. If you've never contributed or worked on a big project, look over some of the resources on how to do that. The `Free Code Camp` link is particularly jucy and coprehensive. Contributing to opensource for the first time can be overwhelming. Don't panic! We're here for you. 
    - Free Code Camp: [How to Contribute to Open Source](https://github.com/freeCodeCamp/how-to-contribute-to-open-source)
    - Open Source Guides: [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
    - [First Timers Only](http://www.firsttimersonly.com/)
    - [Webpack's Contributing Documentation](https://github.com/webpack/webpack/blob/master/CONTRIBUTING.md)
    
1. Familiarize yourself with how Webpack works. If you've never worked with webpack do the [Getting Started tutorial](https://webpack.github.io/docs/tutorials/getting-started/) so you can understand what it's like to work with. If you already know what webpack does, now it's time to get under the hood. It's way easier to contribute when you have an idea of what's *actually happening* in the project you're working on.

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
    - RELEVANT SUB LIBRARIES
        - [tappable](https://github.com/webpack/tapable)
1. Look over available PR's & choose something that fits your tastes and skill levels. Comment on that sla
    - [D0 - 1st Contribution](https://github.com/webpack/webpack/issues?q=is%3Aissue+is%3Aopen+label%3A%22D0%3A+My+First+Commit+%28Contrib.+Difficulty%29%22)
    - [D1 - Easy Difficulty](https://github.com/webpack/webpack/issues?q=is%3Aissue+is%3Aopen+label%3A%22D1%3A+Easy+%28Contrib.+Difficulty%29%22)
    - [X5 - Work Required/ Help Needed](https://github.com/webpack/webpack/labels/X5%3A%20work%20required%20%28PR%20%2F%20Help%20Wanted%29)
1. Ways to get help while you're working:
    - message Rachel & the webpack channel on Learner's Guild's Community slack.
    - comment on the issue and tag [??] and ask for clarifications or feedback.
    - chat with folks on Webpack's internal slack for help.


## TODOS & NOTES
- upgrade the plugins api to match changes in webpack 4.0.0-alpha.
  - ** 12/12: apparently many of these have been done. Search and find any additional to contribute to.
  - where can we reference the api or find what to change?
  - [CONTEXT: issue - webpack 4.0.0-alpha.0 feedback](https://github.com/webpack/webpack/issues/6064)
  - [feat(tapable): upgrade Single|Multi|DynamicEntryPlugin to tapable v1 #6078](https://github.com/webpack/webpack/pull/6078/files)
  - [Improve `PluginEnvironment` helper to support tapable's hooks #6079](https://github.com/webpack/webpack/pull/6079)
- find libraries within the webpack ecosystem to upgrade to es6 syntax.
- update the plugin documentation to for [webpack2](https://webpack.js.org/concepts/plugins/) to be as comprehensive as [webpack1](https://webpack.github.io/docs/plugins.html)

**Expanding Wepack's Availability and Ease of Contribution**
- Make webpack issues easy to find
    - [Up-For-Grabs.net](http://up-for-grabs.net/#/)
    - [issueHub](http://issuehub.io/)
    - TODO evaluate other links in the `Contributing to open source in general` section [here](https://github.com/freeCodeCamp/how-to-contribute-to-open-source)
    - Optimize issue tags for searching.
- Create resources that help people understand the library.
    - video series?
    - monthly Q&A?



