🚫 NaaS: No-as-a-Service
NaaS is a high-performance, asynchronous API built with FastAPI designed to protect your most valuable asset: your time. Whether it's a meeting that could have been an email or an "exciting opportunity," NaaS has the perfect rejection ready for you.

✨ Key Features
Asynchronous Excellence: Built on FastAPI for lightning-fast declines.

Dynamic Excuse Engine: Uses random selection from a curated reasons.json database.

Custom Error Handling: Implements a custom 404 handler for when you can't even be bothered to provide a specific excuse.

JSON Native: Lightweight and easy to integrate into your "I'm busy" workflow.

🛠️ Tech Stack
Backend: Python 3.12+ / FastAPI

Data: JSON-based persistent storage

Server: Uvicorn (ASGI)

🚀 Installation & Usage

Install dependencies:
pip install fastapi uvicorn

Run the server:
uvicorn main:app --reload
