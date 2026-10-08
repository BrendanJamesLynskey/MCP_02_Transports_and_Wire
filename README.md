# MCP Transports & The Wire

Every byte of MCP at the transport layer — stdio framing, the deprecated HTTP+SSE legacy, modern Streamable HTTP, session IDs, resumable streams via `Last-Event-ID`, auth headers, and a fully annotated wire capture of one real session — plus the stateless Streamable HTTP of revision 2026-07-28.

Covers both protocol eras. Revision `2026-07-28` removed sessions (`Mcp-Session-Id`), the GET stream and `Last-Event-ID` resumption; slides 05, 06 and 08 are kept and tagged "before 2026-07-28", and new slides 06b (stateless POSTs, `subscriptions/listen`) and 08b (wire capture with no session) show the current shape, citing the [2026-07-28 specification](https://modelcontextprotocol.io/specification/2026-07-28/basic/transports/streamable-http) (accessed 2026-10-08). Animated companion: [Agent Protocols Explained](https://agent-protocols-explained.vercel.app).

**Live site:** https://brendanjameslynskey.github.io/MCP_02_Transports_and_Wire/

Part of the [Model Context Protocol series](https://github.com/BrendanJamesLynskey/LLMs#model-context-protocol-mcp).
