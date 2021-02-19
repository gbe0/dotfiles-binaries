# bbcp

[bbcp](https://github.com/eeertekin/bbcp) can be used to copy a single large file from one srever to another using multiple threads. This is very useful for links with high latency.

## Install

`bbcp` should be in `$PATH`. Alternatively, copy it to `/bin/`. The binary must be available on both the source and reciever.

## Usage

Example usage:

```bash
bbcp \
  -P 2 -w 2M -s 8 \
  my-huge-file-to-copy \
  root@192.168.x.x:/tmp/
```

For a complete list of arguments check the GitHub page.
