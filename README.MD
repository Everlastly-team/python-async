# Everlastly
Everlastly API for Python. Notarize data using the blockchain. Synchronous version is [here](https://github.com/Everlastly-team/python).

## Installation
```
pip install everlastly
```
## Usage
```python
from everlastly_async import Everlastly

# Sign up and get your keys at https://everlastly.com/keys
e=Everlastly(loop, 'pub key', 'priv key')

example_hash="3e79ffa0e95c435ec8ee50ebb6959259968b4c66852d4fba4fc0876e83b4a0e1"

anchor_result = await e.anchor(example_hash, metadata={"additional info":"隨機詞"})

```

# Feedback

Contact us via support@everlastly.com 

