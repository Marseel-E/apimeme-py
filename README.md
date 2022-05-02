# apimeme-py
A python async wrapper for the APIMeme API
## List meme templates [here](https://apimeme.com)
# Quickstart
```py
import asyncio

from apimeme import Generator

async def main() -> None:
	async with Generator() as session:
		await session.create("advice-dodge")

if __name__ == '__main__':
	asyncio.run(main())
```
[example_output](https://github.com/Marseel-E/apimeme-py/apimeme/meme.jpeg)