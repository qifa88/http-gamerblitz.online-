# GamerBlitz 规则使用指南

## 引用规则

在任何对话中，您可以通过以下方式引用规则：

```
@.cursor/rules/GamerBlitz_AI_Workflow_Rules.md
```

## 规则确认

每次引用规则后，AI 将自动：
1. 确认规则已加载
2. 总结当前上下文
3. 明确标注规则遵守情况

## 规则更新

如需更新规则：
1. 直接编辑 `.cursor/rules/GamerBlitz_AI_Workflow_Rules.md` 文件
2. 在下一次对话中引用更新后的规则

## 规则检查

您可以随时通过以下命令检查规则版本：

```
@.cursor/rules/GamerBlitz_AI_Workflow_Rules.md version
```

## 规则中断

如果需要临时不遵循规则，可以使用：

```
@.cursor/rules/GamerBlitz_AI_Workflow_Rules.md ignore
```

## 规则恢复

如需恢复规则遵循：

```
@.cursor/rules/GamerBlitz_AI_Workflow_Rules.md resume
``` 