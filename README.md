# Commander Core：数字世界的主权Agent调度框架

## 这是什么？

这是数字共生世界的“指挥官”系统。它实现了：

- 主权Agent的意图解析与任务拆解
- 144位职能Agent的调度与协作
- 基于LangGraph的有状态工作流
- 自我复盘与进化机制

## 与宪法的关系

本项目是 `trinary-equivalence` 宪法的参考实现。
所有Agent的初始化必须加载宪法类，所有大脑调用必须通过宪法审查层。

## 快速开始

```bash
git clone https://github.com/ayllyang/commander-core.git
cd commander-core
pip install -r requirements.txt
python examples/taxi_hailing_demo.py
