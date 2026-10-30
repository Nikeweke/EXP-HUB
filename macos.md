

### Find big files in macos 

```sh
du -h -d 1 ~ 2>/dev/null | sort -hr | head -20
```
