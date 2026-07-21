# WinterStorm2030 - High North Governance Wargame

A strategic wargame for testing NATO's Article 4/5 thresholds in the Arctic High North.

## Quick Start

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `streamlit run app.py`

## Game Modes

- **Game Mode**: Strategic decision-making with AI opponent
- **Analyst Mode**: Deep analytical tools for policy assessment

## Features

- Agentic AI Red Team with adaptive behavior
- Real-time OSINT integration via GDELT
- Governance Lab for treaty scoring
- Multiplayer shared state via JSONBin

## Environment Setup

Create `.streamlit/secrets.toml` with:

```toml
[jsonbin]
bin_id = "your_jsonbin_id"
master_key = "your_jsonbin_master_key"