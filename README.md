# Vulnerable Package Versions API

A FastAPI-based microservice that queries the `osv.dev` database for open vulnerability package versions across `Debian` and `Ubuntu` ecosystems.

## Features
- Parallel data fetching using `httpx` and `asyncio`
- Automatic version deduplication
- Alphanumerically sorted version output
- Clean REST endpoint matching specifications

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt