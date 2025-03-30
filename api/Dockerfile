# Dockerfile
FROM python:3.12.2-slim

WORKDIR /app

COPY ./app ./
COPY ./pyproject.toml ./

RUN pip install uv
RUN uv sync

CMD ["uv", "run", "uvicorn", "app.main:app", "--reload", "--host", "0.0.0.0", "--port", "8000"]