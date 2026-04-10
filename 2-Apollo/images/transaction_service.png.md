---
generated-by: image-sidecar
type: image
src: transaction_service.png
path: 2-Apollo/images/transaction_service.png
url: https://raw.githubusercontent.com/PeanutSplash/mc-netease-sdk/main/2-Apollo/images/transaction_service.png
sha: c81c990a79e4f3076f06a8f508e55f4b85e365468f3e15bdf322f0f8ecdc654e
width: 4958
height: 3225
model: google/gemini-3-flash
generated_at: 2026-04-10T02:31:22.293Z
tags: ["architecture-diagram", "software-design", "service-communication", "backend", "game-architecture", "distributed-systems", "flowchart"]
---
# transaction_service.png

A software architecture diagram illustrates the flow of communication between various service modules. A central functional service interacts with a control service, a client, a lobby/game module, and another functional service through NotifyToServiceNode and BroadToService protocols.

## Text in image

```
控制服
NotifyToServiceNode
BroadToService
NotifyToServiceNode
NotifyToServiceNode
客户端
功能服
功能服
BroadToService
NotifyToServiceNode
BroadToService
lobby/game
```
