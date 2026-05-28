# From toy CRUD to real product: building an AI-assisted task management backend in Python

Goals:

1. Learn by doing ( or building) a production-ready service for Tasks with ML components.
2. Organize my own lists of tasks from different services I used in my life.
3. Practice product engineering and development techniques ( integrations, data conflicts, background tasks, AI recommendations, security, audit and testing).

Not goals:

1. Vibe code a whole system from scratch (AI assistance is important and helpful but understanding all the steps of creating is crutial).

## Why yet another TO-DO app?

First, it's simple and understandeble. Second, there a lot of tutorials on the Web how to build a To-Do app from scratch but not many even have a real database for data storing (many of them are using lists or dictionaries for storage during runtime).
Even less are describing **Testing** or **Deployment** problems.

## Stack

- Python
- FastAPI
- Postgres

## How to install

- git
- python
- uv
- docker (k8s?)

## Setup

    git init

    uv init

    uv venv

    source .venv/bin/activate

    python hello.py

Even basic setup says `Hello from todo!`. It's promissing.

From the beggining we already have a lot of files in a directory. Let's add one more for _.gitignore_.
