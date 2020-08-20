# CatParser
__library that allows you to download a random photo or gif with a cat.__
[service](thecatapi.com)


# how use
```python
from sms_ru import CheckCall
import aiohttp


async def main():
 session = aiohttp.ClientSession()
 cat = CheckCall(session=session,api_key="")
 print(await cat.get_photo())
 # jpg or gif or png
```
__file path:"./staticfile/cat.jpg"__

aiohttp>=3
python>=3.7
