## Virtual enviroment
### Install, activate & requirements
In a terminal, from project folder:

```
python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt
```

## Usage example
```
./examples/print-depth.py
```

## For private endpoints: Config API keys
If you want to try private endpoints: Copy/paste your API public and private (secret) keys into file called "kraken.key".

```
./examples/print-open-positions.py
```