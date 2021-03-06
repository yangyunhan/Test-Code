## 项目预览

在这个项目中，你会得到一个基于 web 的用来读取 rss 源的应用。最开始的这个项目的开发者意识到了测试的价值，他们也已经把 [Jasmine](http://jasmine.github.io) 包含在了项目之中，而且甚至已经开始写他们第一个测试用例。但是不幸的是，他们决定去创建一个他们自己的公司，所以我们现在拿到的是一个缺乏完整测试用例的应用，这样是你会参与到这个项目的原因。

## 项目目的

测试是开发过程中一个很重要的部分，很多组织把一个标准的开发过程称之为测试驱动开发。意思就是开发人员在他们开始着手编写应用代码之前先写好测试用例。当然这个时候所有的测试用例都是通不过的，然后他们就开始编写应用代码使测试全部通过。

不管你是在一个推崇测试驱动开发的组织，或者是一个编写测试只是为了防止未来的开发中出现与已有代码冲突的 bug 的团队工作，测试都是我们要掌握的一项重要技能。

## 我会学到什么

你会学到怎么使用 Jasmine 来给已经写好的应用编写一定数量的测用例。这些测试用例既要测试深层次的商业逻辑，也要测试时间处理和 DOM 操作。

## 这对我的职业有何帮助？

* 编写测试需要分析应用中诸如 html , css , javascript 之类的各个层面。当你换了团队工作或者加入到一个新的公司，这项技能尤其重要（译者注：指阅读新的项目代码的能力）
* 长期编写测试会让你拥有不需要手动编写测试去测试所有的功能就能快速分析新的代码是否和已知代码冲突的能力。


# 我如何完成这个项目

查看订阅阅读器项目的[评审标准](https://review.udacity.com/#!/projects/3442558598/rubric)

### 我的任务列表：

- 阅读文档，生成任务列表
- 下载所需项目资源。
- 在浏览器中检查应用程序的各项功能。
- 浏览应用程序 HTML (./index.html)、CSS (./css/style.css) 和 JavaScript (./js/app.js)， 了解其作用方式。
- 浏览 ./jasmine/spec/feedreader.js 中的 Jasmine spec 文件， 查看 Jasmine 文档。
- 编辑 ./js/app.js 中的 allFeeds 变量，使提供的测试出错，然后观察 Jasmine 在应用程序中对该错误进行可视化处理的结果。
- 将 allFeeds 变量返回至传递状态。
- 编写测试对 allFeeds 对象中的每条反馈执行循环操作，并确保其具有定义的非空 URL。
- 编写测试对 allFeeds 对象中的每条反馈执行循环操作，并确保其具有定义的非空名称。
- 编写一个新测试套件，命名 "The menu"。
- 编写测试以确保菜单 (menu) 元素在默认情况下处于隐藏状态。 并要求分析 HTML 和 CSS，以确定 菜单元素的隐藏/显示是如何实现的。
- 编写测试，确保当点击菜单时， 菜单改变其可见性。测试应有两项期望：当点击时，菜单是否显示， 当再次点击时，菜单是否隐藏。
- 编写测试套件并命名 "Initial Entries"。
- 编写测试，确保在调用并执行 loadFeed 函数后， 在 .feed 容器中至少存在一个 .entry 元素。
- 编写测试套件并命名 "New Feed Selection"。
- 编写测试，确保每当 loadFeed 函数加载一条新反馈后， 内容会相应更改。
- 测试不应依赖其他测试的结果。
- 应使用回调函数确保在测试之前 加载反馈。
- 实施针对未定义变量和越界数据访问的 错误处理。
- 编写 README 文件，详细说明成功运行应用程序 所需的所有步骤。如果你添加了额外测试（针对优达学城测试覆盖），则需要提供相关文档，介绍这些未来功能 并说明测试目的。
- 代码重构
- 样式对齐
- 提交作业
- 阅读Code Review的反馈，做相应修改
- 写博客总结
- 刻意练习

## How to use
Clone this repository to your local place, and open the file `index.html` with your browser(Chrome/Firefox). Partly local resources are outside the wall, please use network scientifically.
Then you can enjoy it!

## License
This frogger game is Copyright © 2017 Yunhan Yang. The content of this repository is licensed under a [MIT](https://github.com/yangyunhan/Test-Code/blob/master/LICENSE)