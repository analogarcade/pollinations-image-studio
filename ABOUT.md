# About Canvas AI

Canvas AI is a small local image-generation studio built around the supplied **Simple Image Generator (Pollinations)** n8n workflow.

The original workflow receives a `chatInput`, requests an image from Pollinations, and returns a generated image. This project turns that flow into a focused browser workspace with a local Node.js proxy, a large image-first preview, rotating prompt ideas, recent prompt history, download and copy-link actions, and system-aware dark mode.

## Principles

- Keep the generated image as the primary focus.
- Make the prompt experience inviting without adding clutter.
- Keep the local runtime dependency-free and easy to inspect.
- Respect the user’s screen size and system appearance preference.

## Scope

Canvas AI is a local presentation layer for the workflow. It does not require n8n to run and does not store generated images on the server.
