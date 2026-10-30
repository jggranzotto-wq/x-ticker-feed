# x-ticker-feed

Public JSON feed for the Windows **X Ticker** desktop app.

## Live URL

```
https://raw.githubusercontent.com/jggranzotto-wq/x-ticker-feed/main/feed.json
```

Clients should append `?_=<unix_ms>` and send `Cache-Control: no-cache` / `Pragma: no-cache` because raw.githubusercontent.com CDNs can cache for ~5 minutes.

Refreshed by Grok Bot (X MCP search → GitHub Contents API PUT).
