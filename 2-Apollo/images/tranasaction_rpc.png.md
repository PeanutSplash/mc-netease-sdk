---
generated-by: image-sidecar
type: image
src: tranasaction_rpc.png
path: 2-Apollo/images/tranasaction_rpc.png
url: https://raw.githubusercontent.com/PeanutSplash/mc-netease-sdk/main/2-Apollo/images/tranasaction_rpc.png
sha: 53c9c1f019e5afc20cb2cacc582d08cb4d51f374cc7e496ede066fa42db32edb
width: 5067
height: 4000
model: google/gemini-3-flash
generated_at: 2026-04-10T02:31:17.390Z
tags: ["sequence-diagram", "rpc", "callback", "server-architecture", "backend", "communication-flow", "software-design", "api"]
---
# tranasaction_rpc.png

A sequence diagram illustrates the communication flow between a purple functional server and a green control server. The process includes registering an RPC method, a request from the control server, a service callback, and a response back to the control server.

## Text in image

```
功能服
控制服/lobby/game
RegisterRpcMethodForMod(ServiceCallback)
RequestToServiceMod(ServerCallback)
ServiceCallback
ResponseToServer
ServerCallback
功能服
控制服/lobby/game
```
