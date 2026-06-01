<p align="center">
  <img src="/assets/Banner.jpg" alt="Distance" width="800" />
</p>

# What is this?
A remote desktop streamer based on [Media over QUIC](https://moq.dev) for latency and speed purposes.

# What's inside?
Three repos, with another to come:
 - `client` - The Electron-based desktop client. Workable in a browser, usually.
 - `captured` - A stupid daemon for sending high-speed screen capture over a socket.
 - `agent` -  The host's manager. Sends data to clients, orchestrates certificates, and more.
 - (nonexistent) `relay` - A more managed-interface for using Distance in more complex situations. Great for self-hosting, or groups with many machines.

# Why?
The web has been ready for "good" remote desktop for quite a while, yet nobody has taken full advantage of it yet.
 - Sunshine is great, but it relies on custom UDP and TCP ports.
 - Parsec is great, but WebRTC breaks more than it should and there's poor support for things outside of Windows.
 - VNC may be light, but you're trading that for quality and speed.

The end vision of Distance is a remote desktop app that:
  - Works on plenty of devices
  - Works over the internet or local network
  - Is *very fast*

Got questions? I probably didn't articulate this very well! Shoot me an email at [hi@spacedouut.xyz](mailto:hi@spacedouut.xyz)
