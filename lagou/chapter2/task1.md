# 前端工程化

## 开发脚手架及封装自动化构建工作流

### 1、谈谈你对工程化的初步认识，结合你之前遇到过的问题说出三个以上工程化能够解决问题或者带来的价值

工程化就是把简单重复的工作抽出来作为工具，用来规范工作流程，保证不论是谁去操作，都能产出规范化的预期结果。
第一个就是代码规范问题，代码格式化，不格式化的代码可读写性都很糟糕，后期维护成本也大，为了规范项目的代码，每个项目基本上都配了了eslint或者prettier来规范项目代码，但是实际上还是会有任由代码红色提示不管而去提交代码，所以有了husky用来避免格式不正确的git提交，在提交前进行格式检查，通过才允许提交，这样就能很好的格式化项目代码。
第二个是cli工具，自动化工具，能够把一些复杂通用操作抽出来形成一个简单易用的工具，通过工具能极大提高效率，之前抽业务组件的时候就有用这样的管理工具来进行操作。
第三个就是项目中经常用到的package.json文件里的npm script工作流，其实也是把一些命令或者脚本集中起来到package.json文件里便于管理

### 2、你认为脚手架除了为我们创建项目结构，还有什么更深的意义？

本质上还是提高工作效率，让我们能够快速低成本的配置好一切环境，专注业务开发。善于利用好工具，也能为工作提效不少，抽出重复工作的部分，用工具完成，不仅能提高工作效率，还能减少人为出错的几率。

### 编程题

#### 1、概述脚手架实现的过程，并使用 NodeJS 完成一个自定义的小型脚手架工具
[脚手架工具](https://github.com/leitingting08/Front/tree/master/lagou/chapter2/cli)

#### 2、尝试使用 Gulp 完成项目的自动化构建
[Gulp](https://github.com/leitingting08/Front/tree/master/lagou/chapter2/gulp)

#### 3、使用 Grunt 完成项目的自动化构建
[Grunt](https://github.com/leitingting08/Front/tree/master/lagou/chapter2/grunt)