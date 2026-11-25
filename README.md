# WorkBuddy 每日签到技能

在 Windows WorkBuddy 的「Buddy 加油站」领取每日积分。领取完成后，技能会检查同一项积分余额是否增加了卡片标明的奖励金额，并报告前后余额和实际差额。

## 使用条件

- Windows 上已安装 WorkBuddy，用户已登录本人账号。
- 本机 Codex 会话可操作 Windows 桌面。优先使用 `agent-desktop`，也支持会话中其他获准使用的 Windows 桌面工具。

## 安装

下载 [v1.0.0 发布包](https://github.com/ailuo04/workbuddy-check-in-skill/releases/tag/v1.0.0)，解压到 `$HOME\.agents\skills`。解压后应能找到 `$HOME\.agents\skills\workbuddy-check-in\SKILL.md`。如果技能未出现，重新启动 Codex。

## 使用

在 Codex 输入 `$workbuddy-check-in 帮我领取 WorkBuddy 每日积分，并核对前后余额`。只想查状态时，可以说「看看 WorkBuddy 加油站今天领过没有」。

当天已经领取时，技能会报告卡片状态，并尝试查找领取记录。没有领取前的余额时，无法核对历史余额增量。
