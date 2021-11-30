```
■　Beautiful Soup

from bs4 import BeautifulSoup
import requests


■　htmlを読み込む

load_url = "○○○○"
html = requests.get(load_url)


■　soupで解析

soup = BeautifulSoup(html.content, "html.parser")
```
