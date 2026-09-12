# quotecrate-v2

Small discord.py bot with reminders and quote of the day

## Getting started

```bash
pip install -r requirements.txt
cp .env.example .env  # put your token in .env
```

## Highlights

- Recurring reminders stored in a JSON file
- Rate-limit friendly: single task loop
- Slash commands via discord.py app_commands
- Graceful shutdown flushing state to disk

## How to use

```bash
python bot.py
# then /remind 10m stretch and /quote in your server
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .env.example
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── bot.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```
