# Python Basics

```python
# virtual env
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# packages
pip install requests

# quick script
import requests
r = requests.get("https://example.com")
print(r.status_code)
```