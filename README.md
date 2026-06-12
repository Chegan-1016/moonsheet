# MoonSheet

MoonSheet 是一套计划使用 MoonBit 实现的可解释电子表格计算与公式调试引擎规格。

申报主仓库：[GitLink `Chegan/moonsheet`](https://gitlink.org.cn/Chegan/moonsheet)；开发镜像：[GitHub `Chegan-1016/moonsheet`](https://github.com/Chegan-1016/moonsheet)。

它将负责计算电子表格公式、追踪单元格依赖、执行增量重算，并解释循环引用与错误传播路径。

## 当前状态

当前目录是 MoonSheet 正式开发仓库。仓库已完成 Milestone 0 首轮技术探针，包含可编译的 MoonBit 地址、公式、依赖图、诊断和浏览器适配边界探针。

## 当前开发门禁

必须完成公式解析、依赖与增量重算、循环与错误传播、浏览器调用四个技术探针。探针通过后才进入 MoonSheet MVP 开发。

## 开发验证

```text
moon check --deny-warn
moon test
moon fmt --check
```

## 当前开发范围

MoonSheet 当前处于 Milestone 0，优先验证公式解析、依赖与增量重算、循环与错误传播、浏览器调用。完整产品规格与申报材料在本地维护，不纳入公开代码仓库。

## 当前产品承诺

第一版承诺一条完整旅程：打开工作簿、计算公式、修改输入、局部重算、定位错误根因并完成修复。
