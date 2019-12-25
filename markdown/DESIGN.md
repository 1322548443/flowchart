# flowchart 设计文档

## 组件目标

实现一个可拖拽、连线，方便获取节点与连线数据的，轻量并易用的流程图 vue 组件。

## 版本说明

1.0.0 （不含）以下的版本为不稳定版本，没有单元测试，不保证可用性与 API 兼容，不建议在业务项目中使用。（我先在规则引擎中试试毒）
1.0.0 （包含）预计会加上单元测试，并完善设计文档与 API 文档，需要各位大佬一起维护。

## 输入输出

预计输入有：
1. 一个组件列表，为可拖动的组件集合
2. 默认流程图数据

预计输出：
1. 一个拖拽控件列表
2. 具体流程图界面

