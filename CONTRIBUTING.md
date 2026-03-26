# Contributing

欢迎一起共建 `opc-hub`。

这个仓库更像一个公开目录和资料库，不要求复杂开发能力。只要你能补充准确信息、修正错误链接、完善模板内容，就已经是在贡献。

建议先从 wiki 入口开始阅读：

- [Wiki 首页](./docs/README.md)
- [站点目录](./docs/sites/README.md)
- [资源库](./docs/resources/README.md)

## 你可以贡献什么

- 新的 OPC 站点条目
- 某个城市的线索汇总
- 模板、清单和实用网站
- 资料整理与 FAQ
- 已有条目的修订、补充和纠错

## 提交前的基本要求

- 尽量提供公开来源链接
- 如果信息未完全确认，请明确标注“待核验”
- 不要提交纯传闻、私下聊天截图或未经允许的隐私信息
- 一个文件只做一件事，标题和内容尽量清晰

## 目录约定

### 站点目录

原始内容建议放在：

```text
sites/china/<region>/<city>-<slug>.md
```

例如：

```text
sites/china/east/hangzhou-peifengshe.md
```

### 资源目录

原始内容建议放在：

```text
resources/<type>/<name>.md
```

## 新增站点的流程

1. 复制 [templates/site-entry.md](./templates/site-entry.md)
2. 按字段补充原始内容
3. 存到对应城市或区域目录
4. 如果有必要，再补 `docs/` 里的索引页链接
5. 在 PR 描述里说明来源和变更原因

## 新增资源的流程

1. 复制 [templates/resource-entry.md](./templates/resource-entry.md)
2. 写清楚这个资源解决什么问题
3. 如果是网站，写明官网和典型用途；如果是模板，给出可直接复用内容
4. 如果需要展示在 wiki 中，再补 `docs/resources/` 下的入口页
5. 在 PR 里说明适用场景

## Pull Request 建议

- 标题尽量具体，例如：`新增杭州培风社条目`
- 如果修改多个文件，请在描述里简要说明范围
- 如果是修正信息，请写明修正依据

## 适合先开 Issue 的情况

- 只有线索，没有完整站点资料
- 发现某个条目可能过期，但你不确定
- 你想讨论目录结构或字段调整

## 维护原则

- 信息完整性优先于数量
- 公开可核验优先于道听途说
- 持续增量更新，不追求一次性做完
