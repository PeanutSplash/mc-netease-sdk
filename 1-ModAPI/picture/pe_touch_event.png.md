---
generated-by: image-sidecar
type: image
src: pe_touch_event.png
path: 1-ModAPI/picture/pe_touch_event.png
url: https://raw.githubusercontent.com/PeanutSplash/mc-netease-sdk/main/1-ModAPI/picture/pe_touch_event.png
sha: 8c1b8bd5465f1b65d99a62337dd53a3d20d74fae4719834ab0dce47b7987f9fe
width: 1277
height: 779
model: google/gemini-3-flash
generated_at: 2026-04-10T03:07:17.217Z
tags: ["flowchart", "input-handling", "mobile-gaming", "event-trigger", "ui-design", "technical-diagram", "software-logic", "controls"]
---
# pe_touch_event.png

A technical flowchart illustrating input handling logic for different control modes, including mobile and PC. It maps physical interactions like finger taps and mouse clicks to specific software event triggers.

## Text in image

```
移动端及PC F11模式点触流程
手指按下
松开手指
触发短按
TapBeforeClientEvent
TapOrHoldReleaseClientEvent
移动手指
移动视角
(无事件)
松开手指
(无事件)
短按判定时间
(250ms)
无响应
松开手指 移动手指
长按判定时间
(默认400ms)
触发长按
HoldBeforeClientEvent
移动手指
移动视角
(无事件)
松开手指
长按结束
TapOrHoldReleaseClientEvent
PC F11模式下
鼠标右键
按下右键
RightClickBeforeClientEvent
松开右键
TapOrHoldReleaseClientEvent
PC普通控制模式点击流程
鼠标左键
按下左键
LeftClickBeforeClientEvent
松开左键
LeftClickReleaseClientEvent
鼠标右键
按下右键
RightClickBeforeClientEvent
松开右键
RightClickReleaseClientEvent
新触控-摇杆并瞄准十字线
按下攻击键: LeftClickBeforeClientEvent
松开攻击键: LeftClickReleaseClientEvent
按下交互键: RightClickBeforeClientEvent
松开交互键: TapOrHoldReleaseClientEvent
```
