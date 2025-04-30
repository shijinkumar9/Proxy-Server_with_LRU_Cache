# Proxy Server with LRU Caching

This is a simple multi-threaded HTTP proxy server written in C that supports request forwarding and **Least Recently Used (LRU) caching**. It accepts requests from clients (such as browsers), fetches data from remote servers, caches responses, and serves future repeated requests faster using the LRU strategy.

## 🔧 Features
- Parses client HTTP requests
- Forwards requests to target servers
- Caches responses for faster repeated access in LRU manner

## 🗂️ File Structure
- `proxy_server_with_cache.c` – Main server code
- `proxy_parse.c` & `proxy_parse.h` – Request parsing logic
- `Makefile` – Build script
- `proxy` – Compiled proxy executable
- `a.out`, `.o` files – Build artifacts

## 🛠️ Build Instructions

Ensure you have gcc and make installed.

```bash
make

```
## Run

```bash
./proxy
```
## Author
Shijin Kumar,
Computer Science Student in TKMCE
