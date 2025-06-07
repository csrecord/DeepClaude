pip install uv
uv pip install -r pyproject.toml
python -m uvicorn app.main:app --port 8000 --reload