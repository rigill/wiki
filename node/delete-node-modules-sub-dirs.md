Delete all nodes modules in sub directories.

```bash
find . -name 'node_modules' -type d -prune -print -exec rm -rf '{}' \;
```
