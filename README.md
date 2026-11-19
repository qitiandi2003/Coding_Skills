# Coding Skills

从个人 Codex 开发记录中提炼的中文技能集。按当前问题选择一个入口，每个目录都包含可独立使用的 `SKILL.md`。

| 遇到的问题 | 使用的技能 | 验收示例 |
| --- | --- | --- |
| 给现有工程加功能、修 Bug，担心影响其他调用方 | [coding-skills](skills/coding-skills/SKILL.md) | 地图改名后，已有巡检路线仍能加载 |
| 定位跳变、导航停顿，需要从日志和录包找原因 | [rosbag-diagnosis](skills/rosbag-diagnosis/SKILL.md) | 同一录包对比修复前后，指出首次异常和恢复时刻 |
| Web 刷新丢地图、多端不同步、预览或进度反馈异常 | [web-control-state](skills/web-control-state/SKILL.md) | 手机接续桌面状态，刷新时没有控制请求 |
| 点云出现伪影，或网格指标改善但家具仍难辨认 | [point-cloud-review](skills/point-cloud-review/SKILL.md) | 关闭颜色后，从多个视角仍能辨认椅子的轮廓 |

## 使用

将需要的技能目录放入项目已有的 Codex 技能目录，在请求中用 `$技能名` 指定。也可以直接阅读对应文件，将其中的验收方法用于代码审查。

例如：`用 $rosbag-diagnosis 分析这次导航停顿。对齐录包和日志，找到最先出现异常的环节，再用同一片段验证修复。`
