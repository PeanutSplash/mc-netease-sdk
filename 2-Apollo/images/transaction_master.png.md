---
generated-by: image-sidecar
type: image
src: transaction_master.png
path: 2-Apollo/images/transaction_master.png
url: https://raw.githubusercontent.com/PeanutSplash/mc-netease-sdk/main/2-Apollo/images/transaction_master.png
sha: e350f1551eabd7f8dad42b714f81fd2e1f255d6a466c14c8d7c2c664136c3e8b
width: 1567
height: 2908
model: google/gemini-3-flash
generated_at: 2026-04-10T02:31:20.943Z
tags: ["flowchart", "architecture", "server", "notification", "chinese", "diagram", "system-design", "backend"]
---
# transaction_master.png

A vertical flow diagram shows data movement between three server components. A red 'lobby/game' box and a purple '功能服' (function server) box both send notifications labeled 'NotifyToMaster' to a central dark blue '控制服' (control server) box.

## Text in image

```
lobby/game
NotifyToMaster
控制服
NotifyToMaster
功能服
```
