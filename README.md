# SimpleSplit

## Installation

```
pip3 install -r requirements.txt
```

## Usage

Split a file:

```
python3 simplesplit.py split --input large_file --output nonexistent_directory
```

Split file with a 1GB chunk size:

```
python3 simplesplit.py split --input large_file --output nonexistent_directory --chunk 1GB
```

Combine a file:

```
python3 simplesplit.py combine --input some_directory --output nonexistent_output_file
```

## License

Feel free to bundle this into your software, but please leave the in-code attribution.

Please make it clear if you change this program if you redistribute it.

Please don't license this software under a different license or sublicense it.

This software may be included in commercial software and/or other software as long as this package does not make up a significant portion of the software or is part of the core functionality.
