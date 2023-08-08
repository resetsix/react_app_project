# 基于CRA脚手架的规范配置

适用： react + ts 项目

---

规范配置：`ESLint` + `Prettier` + `husky` + `lint-staged`

包管理器规范：统一使用 `yarn`

模块规范：统一使用`ESModule`

git Commit提交规范：

三个字段：type（必选）、scope（可选）和 subject（必选）

-   类型: 改动描述
-   feat: add yourMessage

(注意，这里的冒号是英文冒号，后面跟着一个空格。)

| 类型     | 描述                                                                                    |
| -------- | --------------------------------------------------------------------------------------- |
| feat     | 新功能（feature）                                                                       |
| fix      | 修补bug                                                                                 |
| docs     | 文档（documentation）变更                                                               |
| style    | 格式（不影响代码运行的变动,空格,格式化,等等）                                           |
| refactor | 重构（即不是新增功能，也不是修改bug的代码变动，例如冗代码删除、重命名变量、简化代码等） |
| perf     | 性能 (提高代码性能的改变)                                                               |
| test     | 增加测试用例或者修改测试用例                                                            |
| build    | 影响构建系统或外部依赖项的更改(maven,gradle,npm 等等)                                   |
| ci       | 对CI配置文件和脚本的更改                                                                |
| chore    | 其他类型，例如构建流程、依赖管理、辅助工具变动等，例如java对非 src 和 test 目录的修改   |
| revert   | 回退                                                                                    |

---
