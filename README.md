# hello-world
Learning here.

##### Web scraping
pip install requests
pip install bs4

import requests
from bs4 import BeautifulSoup as bs

url = "https://www.alltrails.com/us/colorado/boulder"

r = requests.get(url)

