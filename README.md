OmniToolz AI Agents

A personal AI agent army platform built with Vanilla JS, Tailwind CSS, Firebase, and Cloudflare Workers (Llama-3).

Setup Instructions

 1. Cloudflare Worker (Backend)
The backend handles the connection to Llama-3 securely.

1. Navigate to the worker folder: `cd worker`
2. Login to Cloudflare: `npx wrangler login`
3. Deploy: `npx wrangler deploy`
4. Copy the **Worker URL** output by the terminal (e.g., `https://omnitoolz-ai.yourname.workers.dev`).
