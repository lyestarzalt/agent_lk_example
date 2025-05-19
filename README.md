To set up this project:

1. Install packages using `uv sync`, you can install using `pip install uv`

2. Fill in the `.local.env` file with:
   ```
   LIVEKIT_API_KEY=******
   LIVEKIT_API_SECRET=***************************
   LIVEKIT_URL=wss://livekit url
   OPENAI_API_KEY="sk-None-**********"
   ```
   
   Note: The first 3 LiveKit credentials can be found in your account settings in LiveKit Cloud account.

3. Run the application using either:
   - `python main.py dev` or `python main.py start` (then create a sandbox in LiveKit Cloud to chat with the AI agent)
   - `python main.py console` (to chat with the AI without using a sandbox)
