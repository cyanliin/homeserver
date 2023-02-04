# HomeServer

## requirements:
- python 3.7+
- FastAPI & Uvicorn [install guide](https://fastapi.tiangolo.com/)


## API server
### run
```
python -m uvicorn sql_app.main:app --host 0.0.0.0 --port 8000
```

### api url:
```
http://<your.ip>:8000
```

### api docs:
```
http://<your.ip>:8000/docs
```