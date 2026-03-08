<p align="center">
  <img src="/assets/Banner.jpg" alt="Distance" width="800" />
</p>

---

## What's inside

| Repo | Description |
|------|-------------|
| `distance` | Core — C encoder, Python agent, web client |

## How it works

A lightweight agent runs on the host machine and exposes capabilities to any connected client over WebSocket. The client requests what it needs; video stream, file system, shell session, or more. The agent handles the rest.

```
C capture module  →  Python agent  →  Web client
   (encode)           (gateway)        (browser)
```

## Status

Early development. Desktop streaming is functional. Additional capabilities in progress.

---

<p align="center">
  Built for people who notice the lag.
</p>
