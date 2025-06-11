📈 When AI Meets Finance (StockAgent)
StockAgent is a large language model (LLM)-based multi-agent simulation system that mimics real-world stock trading behavior influenced by external factors such as macroeconomics, policy changes, and global events. This project explores how intelligent agents can trade autonomously and respond to realistic market conditions without test data leakage.

🧠 Overview
Can AI agents simulate real-world trading environments to investigate the impact of external factors like economic shifts or corporate events?

StockAgent addresses this by introducing an LLM-powered, multi-agent system designed to:

Emulate investor trading behavior

React to real-time or simulated economic/news-based events

Analyze profitability and behavioral changes

Avoid prior-knowledge bias by eliminating test set leakage

The system is built to help researchers and developers understand the complex interactions in stock trading dynamics.

📄 Research Paper
Title: When AI Meets Finance (StockAgent): Large Language Model-based Stock Trading in Simulated Real-world Environments

arXiv Link: Read the Paper

🏗️ Architecture
Workflow Schematic
The StockAgent workflow is divided into four key phases:

Initial Phase
Sets up traders, capital, and goals.

Trading Phase
Simulates daily buying/selling actions based on LLM decision-making.

Post-Trading Phase
Includes:

Daily Events (e.g., news, economic indicators)

Quarterly Events (e.g., earnings reports)

Special Events Phase
Random impactful events (e.g., financial crises or geopolitical shocks) inserted unpredictably into the simulation.

⚙️ Quick Start
🐍 Set up Environment
bash
Copy
Edit
conda create --name stockagent python=3.9
conda activate stockagent
💾 Clone Repositories
bash
Copy
Edit
# Install PromptCoder (dependency)
git clone https://github.com/dhh1995/PromptCoder
cd PromptCoder
pip install -e .
cd ..

# Clone and set up StockAgent
git clone https://github.com/YOUR_USERNAME/StockAgent
cd StockAgent
pip install -r requirements.txt
🔐 API Keys
Choose your preferred LLM:

For GPT (OpenAI):

bash
Copy
Edit
export OPENAI_API_KEY=your_key_here
For Gemini (Google):

bash
Copy
Edit
export GOOGLE_API_KEY=your_key_here
▶️ Run Simulation
You can start a simulation using your preferred LLM:

bash
Copy
Edit
python main.py --model MODEL_NAME
Default model: gemini-pro

🧾 Citation
If you find this project helpful in your research, please cite us:

bibtex
Copy
Edit
@article{zhang2024ai,
  title={When AI Meets Finance (StockAgent): Large Language Model-based Stock Trading in Simulated Real-world Environments},
  author={Zhang, Chong and Liu, Xinyi and Jin, Mingyu and Zhang, Zhongmou and Li, Lingyao and Wang, Zhengting and Hua, Wenyue and Shu, Dong and Zhu, Suiyuan and Jin, Xiaobo and others},
  journal={arXiv preprint arXiv:2407.18957},
  year={2024}
}
👥 Contributors
@MingyuJ666

@franz-chang

@colmon46

🧰 Tech Stack
Python 3.9

OpenAI / Gemini APIs

Conda environment

LLM-based decision modeling

