# CatParser


# how use
```python
from CatParser import CatApi
import aiohttp
async def main():
 session = aiohttp.ClientSession()
 cat = CatApi(session=session)
 print(await get_photo())
 # jpg or gif or png
```
__file path:"./staticfile/cat.jpg"__

aiohttp>=3
python>=3.7
