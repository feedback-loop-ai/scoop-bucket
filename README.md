# Brokkr Scoop bucket — retired

**This bucket is retired. 0.10.0 is the last version it will carry.**

Brokkr's hosts are Linux and macOS
([decision 0063](https://github.com/feedback-loop-ai/brokkr/blob/main/docs/decisions/0063-windows-is-not-a-host.md)).
Releases after 0.10.0 build no Windows archive, so this manifest is no
longer bumped.

On Windows, use WSL2. It is Linux, and every Linux channel in the
[install table](https://github.com/feedback-loop-ai/brokkr#install)
serves it.

The 0.10.0 manifest stays in place so an existing install keeps
resolving. It was rendered by the release workflow from that release's
attested artifacts and `SHA256SUMS`.
