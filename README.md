# AI-Agent-Web-Browser
🖥️ Run AI Agent in your browser.

This project builds upon the foundation of the browser-use, which is designed to make websites accessible for AI agents.

Features :

WebUI: is built on Gradio and supports most of browser-use functionalities. This UI is designed to be user-friendly and enables easy interaction with the browser agent.

Expanded LLM Support: We've integrated support for various Large Language Models (LLMs), including: Google, OpenAI, Azure OpenAI, Anthropic, DeepSeek, Ollama etc. And we plan to add support for even more models in the future.

Custom Browser Support: You can use your own browser with our tool, eliminating the need to re-login to sites or deal with other authentication challenges. This feature also supports high-definition screen recording.

Persistent Browser Sessions: You can choose to keep the browser window open between AI tasks, allowing you to see the complete history and state of AI interactions.

# Steps to run AI Agent for Windows:

1. pip3 install browser-use in your Command Prompt
2. playwright install chromium --with-deps --no-shell in your Command Prompt
3. Create a folder named ai-agent 
4. Go inside the ai-agent folder - cd desktop and go to cd ai-agent
5. Git clone https://github.com/browser-use/web-ui...
6. Go to cd web-ui and install uv - curl -LsSf https://astral.sh/uv/install.sh | sh
7. Clear the command terminal and open again until web-ui folder
8. Creates an environment - uv venv --python 3.11
9. Activate the env - source .venv/bin/activate
10. uv pip install -r requirements.txt
11.  python webui.py --ip 127.0.0.1 --port 7788
12. You will get the ip and copy and paste the ip
13. Go to google studio and get the gemini api and paste in the browser-ui
14.Run Agent

# Demo :                       

![24205701-98ef-4749-91c6-a3afe74bd9eb](https://github.com/user-attachments/assets/56076e59-d472-4863-a9ae-e5a37d818ff7)

https://github.com/user-attachments/assets/5699afb9-2c10-40c9-bdb4-5ad4df4d3fc2



