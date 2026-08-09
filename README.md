# dual-model-video-prompt

通用 AI 视频提示词引擎：同时覆盖 Seedance 2.5 与 MiniMax H3 两个模型。

本仓库是一个 WorkBuddy skill。把 `SKILL.md` 放到 `~/.workbuddy/skills/dual-model-video-prompt/` 即可使用。

## 核心能力
- 双模型能力矩阵与模型选择决策树
- 统一的导演级 Brief 框架（U1–U9）
- Seedance 2.5 与 MiniMax H3 各自的编译规则
- 去 AI 感微表情 / 运动技法库
- 情绪特写 / 运动跟随 / 对话场景 三套双格式模板

## 用法
在 WorkBuddy 中调用 `dual-model-video-prompt` skill，先产出统一 Brief，再按目标模型编译成 Seedance 或 H3 格式。
