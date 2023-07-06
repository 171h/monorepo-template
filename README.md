# pkg-name

## 使用

- 包管理工具 `pnpm`

```
pnpm dev
pnpm build
```

## 版本控制

- [语义化版本控制](https://semver.org/lang/zh-CN/)
- [约定式提交](https://www.conventionalcommits.org/zh-hans/v1.0.0/)
- [CHANGELOG](https://www.npmjs.com/package/changelogen)

## Commit 规范

- chore: 更新构建脚本等（没有 src 或者 test 的变动）
  - deps: update all non-major dependencies
  - deps: update <nuxt@x.x.x> to x.x.x
- docs: 文档修改
- feat: 新功能
- fix: bug 修复
  - deps: 修复依赖
  - ci: 修复自动化流程配置
- perf: 性能优化
- refactor: 重构（即不是新增功能，也不是修改 bug 的代码变动）
- revert: 回滚
- style: 代码格式修改, 注意不是 css 修改（例如分号修改）
- test: 测试用例新增、修改
- build: 影响项目构建或依赖项修改
- ci: 自动化流程配置修改

## 写代码原则

- **框架思维**（不要写重复代码）
- **高内聚 低耦合**
- **不要重复造轮子**（有现成的用现成的，没有现成的就找现成的，找不到现成的考虑暂时不做了，真的找不到就....（不会真找不到吧））

## Anknowledgements

Nuxt Template based on [vitesse-nuxt3](https://github.com/antfu/vitesse-nuxt3)
