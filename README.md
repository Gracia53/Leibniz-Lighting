# 莱布尼茨的林中空地

**Leibniz’s Lichtung：面向 2046 年的未来人类生命成长空间实验 Agent。**

是一套由创始人掌握价值判断、由总设计 Agent 组织研究与推导的开放工作体系。它从“空间希望让人发生什么改变”出发，把人的成长目标逐步转化为体验机制、空间系统、文化教育内容和可持续运营方式。

## 当前版本

- 版本：`v0.1`
- 状态：`待创始人确认（G0）`
- 当前范围：只实现“第一步：接收与澄清”
- 暂不包含：七个独立 Agent、数据库、网站、自动研究和正式建筑方案

## 三个设计维度

1. **Lifestyle Design**：人在这里如何度过一天、一季和多年。
2. **Cultural Branding**：哪些价值、行为和仪式会形成长期文化。
3. **Human Experience Design**：人在其中如何感受、行动、连接、创造并发生改变。

## v0.1 如何使用

1. 阅读 [`docs/PROJECT_CHARTER_v0.1.md`](docs/PROJECT_CHARTER_v0.1.md)，由创始人确认或修改项目边界。
2. 将 [`prompts/ORCHESTRATOR.md`](prompts/ORCHESTRATOR.md) 作为总设计 Agent 的长期指令。
3. 将 [`prompts/INTAKE_CLARIFICATION.md`](prompts/INTAKE_CLARIFICATION.md) 作为第一次对话任务。
4. 输入一段未经整理的创始人愿景。
5. 使用 [`evals/ACCEPTANCE_CHECKLIST.md`](evals/ACCEPTANCE_CHECKLIST.md) 检查输出是否合格。
6. 通过 G0 前，不进入研究、体验或空间方案设计。

## 项目结构

```text
docs/       项目宪章、角色与治理规则
prompts/    总设计 Agent 与具体工作步骤的指令
memory/     八类共享项目记忆的统一结构
evals/      测试案例与验收清单
```

## 核心治理原则

- 创始人决定项目相信什么，以及不做什么。
- Agent 可以研究、推理、质疑和建议，但不能替创始人作出价值裁决。
- 未确认的信息必须标记为假设，不能写成事实。
- 七种专业视角用于交叉判断，不得拼接为七份互相割裂的回答。
- 重大结论必须保存依据、异议、风险和重新评估条件。
- 项目记忆同时保存成功、失败和被淘汰方案。

## 开放协作

本项目以公开、可追溯、可讨论为原则。代码与仓库内容当前采用 MIT License。外部贡献应清楚标记事实来源、推论、价值主张和待验证假设。

