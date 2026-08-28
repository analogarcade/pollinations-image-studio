# Architecture

```text
Browser prompt
      ↓
GET /api/image?prompt=...
      ↓
Local Node.js proxy
      ↓
Pollinations image API
      ↓
Image stream returned to browser
```

The server uses Node.js built-ins only. It URL-encodes prompts, constrains image dimensions, requests the image from Pollinations, and streams the response back to the browser. The frontend handles prompt ideas, history, image actions, layout, and theme styling locally.
