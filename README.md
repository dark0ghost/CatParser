# CatParser
__library that allows you to download a random photo or gif with a cat__
[service](thecatapi.com)


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
