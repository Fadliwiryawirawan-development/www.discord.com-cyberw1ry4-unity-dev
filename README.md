
This API & Web provides access to hero analytics, in-game performance data, academy resources, player endpoints, and utility tools. It is designed with a consistent RESTful structure, supports flexible hero identifiers (ID or name), and delivers standardized responses for seamless integration into applications, dashboards, analytics systems, and internal tooling.

Important

Built with Dedication: This project is the result of over wakatime of meticulous coding, architecting, and performance tuning to ensure the best developer experience.

Features
Public REST API for MLBB data: user, mlbb, academy, and addon service groups
Web playground for all endpoints: form-driven execution at /web/*
Flexible hero identifier support: hero ID or hero name (including compact slug-like names)
Readable response views: switch between Key-Value and Key-As-Header table modes
Language snippets: curl, python, javascript, go, node, php, java, csharp
Copy helpers: copy snippet, copy response, copy JWT from signed-in menu
Auth modal flow for user endpoints: Send VC + Login in one popup
JWT-aware navbar state: profile photo, username, country, roleId(zoneId), sign out
Tutorial & blog pages: step-by-step guides with SEO-ready detail pages
OpenAPI-first docs: Swagger UI, ReDoc, and OpenAPI JSON
Documentation
Title	Link	Description
Website Home	mlbb.rone.dev	Main landing page with quick access to Demo Website and API Docs.
Tutorial and Blog	mlbb.rone.dev/blog	Guides, tutorials, and release/changelog posts.
Web Playground	mlbb.rone.dev/web	Interactive endpoint workspace for executing API requests from browser forms.
OpenMLBB SDK Docs	mlbb.rone.dev/openmlbb	Structured Python SDK docs for academy, mlbb, user, and addon clients with endpoint-level examples.
TypeScript SDK (Alternative)	npmjs.com/package/mlbb-sdk	Alternative SDK option for TypeScript/JavaScript projects.
Swagger UI	mlbb.rone.dev/api/docs	OpenAPI-powered docs with live request execution and authorization support.
ReDoc	mlbb.rone.dev/api/redoc	Alternative API documentation view optimized for reference reading.
OpenAPI JSON	mlbb.rone.dev/api/openapi.json	Raw OpenAPI schema for tooling, SDK generation, and integrations.
Web Interface Highlights
Home page provides two entry points: Open Demo Website and Open API Docs
Demo Website (/web/*) is recommended for most usage and exploration
Sign In modal supports Send VC then Login with VC (same role/zone fields, VC expires in 5 minutes)
Signed-in menu shows profile details and Copy JWT for quick docs authorization
Endpoint cards include request forms, snippets, readable/JSON responses, and copy actions
Readable response section supports view switching: Key-Value or Key As Header
Base URLs
https://mlbb.rone.dev/                  # Landing page
https://mlbb.rone.dev/blog              # Tutorial and blog list
https://mlbb.rone.dev/blog/{slug}       # Blog detail page
https://mlbb.rone.dev/web               # Web interface (redirects to /web/user)
https://mlbb.rone.dev/web/user          # User endpoints playground
https://mlbb.rone.dev/web/mlbb          # MLBB endpoints playground
https://mlbb.rone.dev/web/academy       # Academy endpoints playground
https://mlbb.rone.dev/web/addon         # Addon endpoints playground
https://mlbb.rone.dev/openmlbb          # OpenMLBB docs (redirects to /openmlbb/user)
https://mlbb.rone.dev/openmlbb/user     # OpenMLBB user client docs
https://mlbb.rone.dev/openmlbb/mlbb     # OpenMLBB mlbb client docs
https://mlbb.rone.dev/openmlbb/academy  # OpenMLBB academy client docs
https://mlbb.rone.dev/openmlbb/addon    # OpenMLBB addon client docs
https://mlbb.rone.dev/api               # API index/status
https://mlbb.rone.dev/api/docs          # Swagger UI
https://mlbb.rone.dev/api/redoc         # ReDoc
https://mlbb.rone.dev/api/openapi.json  # OpenAPI schema
Python SDK (PyPI)
Install:

pip install OpenMLBB
Usage:

from OpenMLBB import OpenMLBB

client = OpenMLBB()

# same endpoint groups as API routers
academy_data = client.academy.roles(lang="en")
mlbb_data = client.mlbb.heroes(size=10, index=1, order="desc", lang="en")

print(academy_data)
print(mlbb_data)
SDK defaults:

Base endpoint: https://mlbb.rone.dev/api
Response type: JSON payload mapped to Python dictionary
User-Agent: RoneAI-OpenMLBB-Python-SDK
TypeScript SDK (Alternative)
If your project is using TypeScript or JavaScript, you can use mlbb-sdk as an alternative SDK.

Install:

npm install mlbb-sdk
Quick start:

import { createMlbbClient } from "mlbb-sdk";

const client = createMlbbClient({ lang: "en" });

const heroes = await client.mlbb.getHeroes();
const roles = await client.academy.getRoles();

console.log(heroes);
console.log(roles);
Automated Release Rules (4.x.x)
Workflow file: .github/workflows/python-publish.yml
Version source for release/tag/PyPI: PROJECT_VERSION default in app/core/config.py
Version tags use format: 4.x.x (no v prefix)
Push behavior:
main branch creates stable GitHub release and publishes to PyPI.
non-main branch creates prerelease only when ENABLE_NON_MAIN_PRERELEASE="true".
Update process:
Manually set the next version in app/core/config.py before pushing release commit.
Workflow still automates release build, tag, GitHub release, and PyPI publish.
API Coverage
Full endpoint lists, operation summaries, and request/response schemas are always available in:

https://mlbb.rone.dev/api/docs (Swagger UI)
https://mlbb.rone.dev/web (interactive web endpoint explorer)
This ensures API coverage documentation stays up to date with every release without maintaining manual endpoint lists in README.

Changelog
See Releases for migration notes and updates.

License & Attribution
This project is licensed under the BSD 3-Clause License. Attribution must be preserved to Moonton (the creator of Mobile Legends) and either ridwaanhall (the maintainer of this API project) or RoneAI (the organization behind this API) in all downstream usage and derivative projects.

Notice
All data is sourced from publicly available content and provided for educational, analytical, and community purposes only. Visual assets and references are used respectfully and do not imply official partnership.

Example Attribution (README or app footer)
Powered by MLBB Public Data API Data © Moonton (Mobile Legends) API maintained by ridwaanhall / RoneAI

Local Development (internal)
Setup
# skip this if already have
uv init # create pyproject.toml
uv add fastapi # add deps
uv add pytest --dev # add deps for dev

# use this if already have pyproject.toml and uv.lock
uv sync
cp .env.example .env
Run
Development
fastapi dev
Production
fastapi run
Deploy
# deploy via fastapicloud
fastapi deploy
Test
pytest
Environment Variables
SECRET_KEY
RONE_DEV_ACCESS_KEY
RONE_DEV_ACCESS_KEY_V2
See .env.example for full configuration.



<img width="670" height="670" alt="cyberw1ry4-AI-Tools-Vullners-CVE-Titans" src="https://github.com/user-attachments/assets/5576d576-d7e7-4edc-bb27-6a4189e1c5d6" />



https://github.com/user-attachments/assets/9b302faf-746f-4624-9a09-74893c9f6c6b





# nisa sabyan mantan SMP yanoery90 smk taruna terpadu boash borcess 2012 , fix dont judged me again

# https-discord.com-download
discor kener plugin game agar nyaman di network asik tanpa cheater juga gak kena banned sama jailbreak bersama kami custom sistem gaming  
from langchain_discord.tools.discord_read_messages import DiscordReadMessages
from langchain_discord.tools.discord_send_messages import DiscordSendMessage

# Create instances of each tool
read_tool = DiscordReadMessages()
send_tool = DiscordSendMessage()

# Read the last 5 messages from channel 1234567890
read_result = read_tool({"channel_id": "1234567890", "limit": 5})
print(read_result)

# Send a message to the same channel
send_result = send_tool({"channel_id": "1234567890", "message": "Hello from Python!"})
print(send_result)
Using the Toolkit
You can also use DiscordToolkit to automatically gather both tools:

from langchain_discord.toolkits import DiscordToolkit

toolkit = DiscordToolkit()
tools = toolkit.get_tools()

# tools[0] should be DiscordReadMessages, tools[1] is DiscordSendMessage
read_tool = tools[0]
send_tool = tools[1]

# Example usage
print(read_tool({"channel_id": "1234567890", "limit": 5}))
print(send_tool({"channel_id": "1234567890", "message": "Hello from toolkit!"}))
Tests
If you have a tests folder (e.g. tests/unit_tests/), you can run them (assuming Pytest) with:

pytest --maxfail=1 --disable-warnings -q
Make sure your DISCORD_BOT_TOKEN is set or your tests are mocked so they don’t require a real token.

License
MIT License

Further Documentation
For more details, see the docstrings in:

discord_read_messages.py
discord_send_messages.py
toolkits.py for DiscordToolkit
Official Discord Developer Docs: https://discord.com/developers/docs/intro

LangChain GitHub for general LangChain usage and tooling.
