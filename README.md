<div align="center">
    <h3>xdedup</h3>
    <h5>find and remove duplicates</h5>
</div>


```bash
xdedup
  --plan          create a delete script instead of deleting
  --dry-run       perform a trial run with no changes made
  --ext EXT       file extensions to look for (default: mkv)
  --tool NAME     hashing tool (default: b3sum)
  -h, --help      show this help
```

## Installation

```bash
# Clone the repo
git clone git@github.com:metaory/xdedup.git

# Navigate to repo
cd xdedup

# Give execution permissions
chmod +x xdedup

# Link it somewhere in your PATH
ln -svf $PWD/xdedup /usr/bin/xdedup

# Use it anywhere
xdedup
```

## License

[MIT](LICENSE)

