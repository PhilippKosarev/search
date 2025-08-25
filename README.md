# Search
A simple CLI utility to find that *one* file somewhere among the 5 million files on your system.

## Features
- Written in Python
- Fast and responsive
- Tells you what it's doing
- Utilises all the CPU threads

## Example usecase
Finding all the `.desktop` files on your system.
```
$ search for .desktop /
Found 5,529,282 files in 6.82s.
Found 12,022 matches in 7.83s.
```

## Installing
Install dependencies:
```
pip install libjam==0.1.5
```
Then just put the `search` file in the `~/.local/bin/` directory.
Or run this shady script which does that for you:
```
cd ~/.local/bin && { curl -Os https://raw.githubusercontent.com/philippkosarev/search/main/search ; cd -; }
```