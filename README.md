# AI Trip Planner

AI Trip Planner is a small toolkit + demo app for generating travel plans and retrieving trip-related information using modular tools and an agentic workflow.

## ✨ Features

- Modular tool set for: place search, weather, currency conversion, expense calculations, etc.
- Agentic workflow to compose tools into higher-level trip planning tasks (`agent/agentic_workflow.py`).
- Streamlit demo UI (`streamlit_app.py`) for interactive queries and quick prototyping.
- Lightweight utilities for integration and testing.

## 🚀 Quickstart

Prerequisites:
- Python 3.8+ (project was developed with Python 3.10)
- Git

1. Clone the repo

\`\`\`bash
git clone https://github.com/Abdul770562/AI_Trip_Planner.git
cd AI_Trip_Planner
\`\`\`

2. Create and activate virtual environment

Windows (PowerShell):

\`\`\`powershell
python -m venv env
.\env\Scripts\Activate.ps1
\`\`\`

3. Install dependencies

\`\`\`bash
pip install -r requirements.txt
# optional: install in editable mode for development
pip install -e .
\`\`\`

## ▶️ Run the Streamlit demo

\`\`\`bash
streamlit run streamlit_app.py
\`\`\`

Open the URL displayed by Streamlit (usually http://localhost:8501).

## 🔧 Project layout

- `agent/` — agentic workflow and orchestration
- `tools/` — individual tool implementations (place search, weather, currency, etc.)
- `utils/` — helper utilities used by tools and the agent
- `config/config.yaml` — runtime configuration
- `streamlit_app.py` — simple interactive demo
- `main.py` — entrypoint for scripted runs or examples

## ⚙️ Configuration

Edit `config/config.yaml` to change API keys, default locations, or other runtime settings. Keep secrets out of version control and set them via environment variables when possible.

## Contributing

Contributions are welcome. Please:

1. Open an issue to discuss larger changes
2. Create a feature branch
3. Submit a PR with a clear description and tests where applicable

## License

No license file is included in this repository. If you want this project to be open-source, add a `LICENSE` file (e.g., MIT) to the root.

## Contact

Repository owner: Abdul770562

---