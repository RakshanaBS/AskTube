# AskTube
AskTube is a Chrome extension designed to make YouTube content searchable and interactive. It allows users to ask natural language questions about any video they’re watching and receive answers directly from the transcript—saving time and improving learning efficiency.

The extension retrieves transcripts by parsing YouTube’s HTML (no API key needed), processes them into timestamped segments, and uses LangChain with Gemini 1.5 Pro to retrieve relevant context and generate accurate responses.

Technologies used include TypeScript, Vite, LangChain.js, and the Chrome Extensions API. This project gave me hands-on experience with Chrome extension architecture (Manifest V3), multi-script coordination, and LLM integration. While there’s still room for improvement in areas like UI, error handling, and transcript availability, AskTube shows how AI can enhance how we learn from video content.

