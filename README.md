# Simple Directory Exposer

A tiny Python HTTP server that exposes **all files in the current directory and its subdirectories** over a local web server.

Uses Python’s built-in `http.server` — no dependencies.

---

## Usage

```bash
python server.py
```

Then open:

```
http://localhost:8000
```

All files and folders in the current directory are accessible.

---

## Notes

* Serves **everything** in the current and sub directories
* Local use only — **not secure**
* Stop with **CTRL + C**
