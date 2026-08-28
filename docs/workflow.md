# n8n Workflow Notes

Input workflow: `source/Simple Image Generator (Pollinations).json`

The workflow contains three nodes:

1. Chat trigger receiving `chatInput`.
2. HTTP Request to `https://image.pollinations.ai/{{ $json.chatInput }}`.
3. Chat response confirming the generated image.

Canvas AI mirrors the image-request behavior locally and adds a browser-focused interface around it.
