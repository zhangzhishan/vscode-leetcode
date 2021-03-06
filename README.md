<img align="right" width="150" height="150" src="https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/LeetCode.png">

# LeetCode
[![Travis CI](https://travis-ci.org/jdneo/vscode-leetcode.svg?branch=master)](https://travis-ci.org/jdneo/vscode-leetcode)
[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version-short/shengchen.vscode-leetcode.svg)](https://marketplace.visualstudio.com/items?itemName=shengchen.vscode-leetcode)
[![license](https://img.shields.io/github/license/jdneo/vscode-leetcode.svg)](https://github.com/jdneo/vscode-leetcode/blob/master/LICENSE)
[![Gitter](https://badges.gitter.im/vscode-leetcode/Lobby.svg)](https://gitter.im/vscode-leetcode/Lobby)

Solve LeetCode problems in VS Code.
- [中文](#中文)
- [English](#english)

# English
## Requirements
- [Node.js 8+](https://nodejs.org)
    > NOTE: Please make sure that `Node` is in your `PATH` environment variable. You can check this by running: `node -v`.

## Features
- Sign in/out to LeetCode
- Switch and create session
- Show problems in explorer
  > Note: To show the locked problems, please set `leetcode.showLocked` to **true**
- Search problems by keywords
- Test solutions by customized test case
- Submit solutions to LeetCode

### Sign In and Sign Out
![SignInOut](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/signinout.gif)

### Switch and Create Session
![SwitchSession](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/switchsession.gif)

### Show Problems in Explorer <sup>1</sup>
![ShowProblem](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/showproblem.gif)

### Search Problems by Keywords <sup>1</sup>
![SearchProblem](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/searchproblem.gif)

### Test solutions by customized test case <sup>2</sup>
![TestSolution](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/testsolution.gif)

### Submit Solutions to LeetCode <sup>2</sup>
![SubmitSolution](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/solveproblem.gif)

<sup>1</sup> If no folder is opened in VS Code, the extension will save the problem files in `$HOME/.leetcode/`. <br/>
<sup>2</sup> If you trigger the `Submit to LeetCode` and `Test in LeetCode` commands in the Command Palette, the extension will upload the current active file in editor.

## Commands
This extension provides several commands in the Command Palette (F1 or Ctrl + Shift + P):
- **LeetCode: Sign in** -  Sign in to LeetCode
- **LeetCode: Sign out** -  Sign out to LeetCode
- **LeetCode: Select session** -  Select one session and make it active
- **LeetCode: Create new session** -  Create a new session
- **LeetCode: Refresh** -  Refresh the LeetCode Explorer
- **LeetCode: Search Problem** -  Search for problems by keywords
- **LeetCode: Test in LeetCode** - Test solution file by customized test case
- **LeetCode: Submit to LeetCode** -  Submit the solution file to LeetCode
- **LeetCode: Switch endpoint** - Switch the LeetCode endpoint. (LeetCode or LeetCode-cn)

## Known Issues:
- This extension will infer the current target problem according to the active editing file. Please do not change the file name.

## Release Notes

Refer to [CHANGELOG](https://github.com/jdneo/vscode-leetcode/blob/master/CHANGELOG.md)

## Acknowledgement

- This extension is based on [@skygragon](https://github.com/skygragon)'s [leetcode-cli](https://github.com/skygragon/leetcode-cli) open source project.
- Special thanks to our [contributors](https://github.com/jdneo/vscode-leetcode/blob/master/ACKNOWLEDGEMENTS.md).



# 中文
## 运行条件
- [Node.js 8+](https://nodejs.org)
    > 注意: 请确保`Node`在`PATH`环境变量中，您可以通过执行：`node -v`进行查看。

## 功能
- 登入 / 登出 LeetCode
- 切换及创建 session
- 在 Explorer 中展示题目
  > 注意: 如果想要展示付费题目，您需要将 `leetcode.showLocked` 设置为 **true**
- 根据关键字搜索题目
- 用自定义测试用例测试答案
- 向 LeetCode 提交答案

### 登入及登出
![SignInOut](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/signinout.gif)

### 切换及创建 session
![SwitchSession](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/switchsession.gif)

### 在 Explorer 中展示题目 <sup>1</sup>
![ShowProblem](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/showproblem.gif)

### 根据关键字搜索题目 <sup>1</sup>
![SearchProblem](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/searchproblem.gif)

### 用自定义测试用例测试答案 <sup>2</sup>
![TestSolution](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/testsolution.gif)

### 向 LeetCode 提交答案 <sup>2</sup>
![SubmitSolution](https://raw.githubusercontent.com/jdneo/vscode-leetcode/master/resources/gif/solveproblem.gif)

<sup>1</sup> 如果 VS Code 中没有已打开的文件夹，插件会将题目文件存储于 `$HOME/.leetcode/` 目录下。<br/>
<sup>2</sup> 如果您通过命令面板触发 `Submit to LeetCode` 和 `Test in LeetCode` 命令，本插件将会提交当前文件至 LeetCode。

## 命令
该插件在命令面板（F1 或 Ctrl + Shift + P）中支持下列命令：
- **LeetCode: Sign in** -  登入 LeetCode
- **LeetCode: Sign out** -  登出 LeetCode
- **LeetCode: Select session** -  激活一个已有的答题进度存档
- **LeetCode: Create new session** -  创建一个新的答题进度存档
- **LeetCode: Refresh** -  刷新左侧题目列表视图
- **LeetCode: Search Problem** -  根据关键字搜索题目
- **LeetCode: Test in LeetCode** - 用自定义测试用例进行测试
- **LeetCode: Submit to LeetCode** -  提交答案到 LeetCode
- **LeetCode: Switch endpoint** - 变更 LeetCode 终端（LeetCode 或 领扣）

## 已知问题
- 本插件会根据文件名称推测当前的目标题目，因此建议不要改变文件名。

## 更新日志

请参考[更新日志](https://github.com/jdneo/vscode-leetcode/blob/master/CHANGELOG.md)

## 鸣谢

- 本插件基于[@skygragon](https://github.com/skygragon)的[leetcode-cli](https://github.com/skygragon/leetcode-cli)开源项目制作。
- 特别鸣谢这些[贡献者们](https://github.com/jdneo/vscode-leetcode/blob/master/ACKNOWLEDGEMENTS.md)。
