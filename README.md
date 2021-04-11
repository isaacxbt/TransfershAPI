# transfer.sh-api

Fileleaks is a Python library for upload files on [transfer.sh](https://transfer.sh/). 

## About

This **unofficial** Python API was created to make uploading and downloading files from [transfer.sh](https://transfer.sh/) simple

## Installation


```bash
pip install transfersh-cli && pip install wget
```

## Usage

## Upload files (console)

```bash
transfersh "filepath"
```

## Download files
```python
import wget


try:

    download = wget.download("direct URL") # How? https://encrypting.host/uRZkzQnPb8.gif?key=R4WzyRMxLBDjcp
  
except Exception as e:
    print(e)
    # your file can't be downloaded.
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
