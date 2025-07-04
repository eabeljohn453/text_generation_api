# Create a Virtual Environment

```bash
python -m venv venv
```

# Activate the venv

```bash
venv/Scripts/activate
```

# Install required libraries

```bash
pip install fastapi uvicorn torch numpy transformers
```

# Run the server

```bash
uvicorn main:app --reload
```
