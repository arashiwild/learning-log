# Python Virtual Environment

Virtual environment mengisolasi dependencies per project.

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

pip install -r requirements.txt
deactivate
```

Hindari konflik versi package antar project.
