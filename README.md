# Proxy Server with Caching

This is a simple proxy server written in C that implements request forwarding and basic caching.

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

```bash
make

```
## Run

```bash
./proxy
```
## Author
Shijin Kumar
Computer Science Student in TKMCE
