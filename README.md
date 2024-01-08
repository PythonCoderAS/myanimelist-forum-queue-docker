# myanimelist-forum-queue Docker

Source: https://github.com/PythonCoderAS/myanimelist-forum-queue

## Running

```bash
docker run -v "./secrets.py:/app/myanimelist_forum_queue/secrets.py" ghcr.io/pythoncoderas/myanimelist-forum-queue
```

## Prerequisites

Needs an file at `/app/myanimelist_forum_queue/secrets.py` with the content:

```python
csrf_token="Your MAL CSRF token"
```
