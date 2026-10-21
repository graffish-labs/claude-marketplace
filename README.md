# Graffish Labs — Claude Code plugin marketplace

The public marketplace for Graffish Labs' external Claude Code plugins (support, connect, telemetry).

**Install guide:** https://get.ops.graffish.com/claude/

**In short (Claude Desktop):** Settings → Plugins → Add → Add from a repository → `graffish-labs/claude-marketplace`
→ Sync, then install **support** (connect and telemetry come with it).

This repo holds only `.claude-plugin/marketplace.json`. It is written by the Graffish ops server after each checked
release; the plugin zips are served from `https://get.ops.graffish.com/claude/` with their sha256 in that file. Do not
edit it by hand.
