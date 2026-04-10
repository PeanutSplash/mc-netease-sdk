---
generated-by: image-sidecar
type: image
src: transaction_game.png
path: 2-Apollo/images/transaction_game.png
url: https://raw.githubusercontent.com/PeanutSplash/mc-netease-sdk/main/2-Apollo/images/transaction_game.png
sha: 45c20ec4f410c93686388d4fbc23d3ff8fc09b440be5fc738d4cf0bc6dc74702
width: 4942
height: 1850
model: google/gemini-3-flash
generated_at: 2026-04-10T00:43:04.572Z
tags: ["architecture", "flowchart", "server-node", "notification-flow", "lobby-game", "backend", "diagram", "system-design"]
---
# transaction_game.png

A system architecture diagram shows data flow between four components: Client, Function Server, Lobby/Game, and Control Server. Various notification methods like NotifyToServerNode and BroadcastToServerByType connect these nodes with directional arrows.

## Text in image

```
功能服
NotifyToServerNode
BroadcastToServerByType
NotifyToServer
NotifyToServerNode
客户端
lobby/game
控制服
```
