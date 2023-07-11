# name1
Description

# Mein Codebeispiel

Hier ist mein Beispielcode:

```python
import requests

def get_data(url):
    response = requests.get(url)
    if response.status_code == 200:
        data = response.json()
        return data
    else:
        return None

url = "https://api.example.com/data"
result = get_data(url)
print(result)
