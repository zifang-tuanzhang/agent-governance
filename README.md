# agent-governance · 多智能体治理与编排实践

> 一套源于真实 Agent 实践的 Markdown 治理参照系。
>
> 从「试图用三份文件控制 Agent」开始，经过实践翻车，逐渐演化为一套适配 Agent Framework 的编排思想。

---

## 🧭 这里记录什么？

这个仓库最初相信：

**SOUL / CONSTITUTION / AGENTS 三份文件，可以塑造一个 Agent。**

后来实践让我发现：

- Prompt 很强，但它终究是**软控制**，无法单独提供确定性。
- 三份文件不能脱离 Agent Framework 作为外挂独立存在。
- 真正需要确定性的部分，应交给 **Workflow / State / Runtime / Permission**。
- SOUL / CONSTITUTION / AGENTS 更适合作为一套**编排思想与参照系**。

因此，这里既保留当时的模板，也保留后来对它们的重新理解。

---

## 📚 核心内容

| 文件 | 作用 |
| --- | --- |
| [01-Agent 编排治理](../01-Agent 编排治理.md) | 多 Agent 编排总体治理框架 |
| [02-SOUL_template](../02-SOUL_template.md) | Agent 身份 / 判断 / 价值参照 |
| [03-CONSTITUTION_template](../03-CONSTITUTION_template.md) | Agent 边界 / 红线 / 权限参照 |
| [04-AGENTS_template](../04-AGENTS_template.md) | Agent 工作方式 / 协作参照 |
| [05-AGENTS_template(编排上下文路由)](../05-AGENTS_template(编排上下文路由).md) | 上下文与编排路由 |
| [06-ceo_template](../06-ceo_template.md) | 总控 / 决策角色参照 |
| [07-路由 系统导航_template](../07-路由 系统导航_template.md) | 系统导航与路由 |

### 思想演化

- [00_从三份文件到体系](./00_从三份文件到体系.md) — 从“三份文件”到编排体系
- [08_两次翻车与编排边界](./08_两次翻车与编排边界.md) — 两次实践翻车与尚未完成的观察

---

## ⚠️ 一个重要说明

这里的模板**不是确定性控制 Agent 的魔法**。

它们记录的是一段真实的实践过程：

> **从以为可以控制，到发现不能确定控制，再到理解应该如何与 Framework 分工。**

旧版本没有被删除。

因为错误本身也是实践记录。

---

## 🧩 核心思想

> **Prompt 负责影响，Workflow / State 负责约束过程，Runtime / Permission 负责约束实际动作。**

而最终是否成立：

**交给现实验证。**

---

MIT License · © 2026 子星明
