# MobileNet Image Classifier

A FastAPI web application that uses MobileNetV2 pretrained on ImageNet to classify uploaded images.

## Run locally

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn app:app --reload
```

Open http://127.0.0.1:8000

## Render

Build command:

```bash
pip install -r requirements.txt
```

Start command:

```bash
uvicorn app:app --host 0.0.0.0 --port $PORT
```

The app exposes `/health`, `/predict`, and the web interface at `/`.
