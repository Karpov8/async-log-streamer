# Async Log Streamer ⚡

A lightweight, zero-dependency (almost) asynchronous server log parser and router for Python ecosystems.

While massive enterprise solutions like ELK or Splunk exist, smaller infrastructure and DevOps teams often quietly depend on fast, non-blocking log analysis for real-time monitoring. `async-log-streamer` fills this critical gap by providing an async-first approach to tailing, parsing, and routing log files natively in Python without heavy Java or Node.js overhead.

## Features
- 🚀 **Fully Asynchronous**: Built on `asyncio` to prevent I/O blocking during massive log bursts.
- 🧩 **Regex-based Routing**: Easily define custom schemas for Nginx, Apache, or custom application logs.
- 🔌 **Pluggable Architecture**: Currently expanding pipelines for direct Webhook and WebSocket integrations.

## Installation (Dev)
Currently in active beta. Clone the repository to try it locally:
```bash
git clone [https://github.com/Karpov8/async-log-streamer.git](https://github.com/Karpov8/async-log-streamer)
cd async-log-streamer
pip install -r requirements.txt 
