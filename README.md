<div align="center">
    <h3>xdedup</h3>
    <h5>find and remove duplicates</h5>
</div>

---

designed for large drives, with terabytes of data,
jobs that could take even hours, 
with stored hash results on disk for intrupted jobs,
so you can stop a long job mid way and continue later,
the default hashing function is `b3sum` [BLAKE3](http://archlinux.org/packages/extra/x86_64/b3sum/)
you can provide your hashing tool with `--tool` option, 
to use other hashing functions like `sha256sum`, `sha512sum`, `md5sum`, ...

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

