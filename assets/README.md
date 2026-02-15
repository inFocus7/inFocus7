# ASCII

For the zsh images, I used [TheZoraiz/ascii-image-converter](https://github.com/TheZoraiz/ascii-image-converter?tab=readme-ov-file#homebrew).

```sh
# after aliasing `ascii-image-converter` to `ascii`...
ascii -C -d 80,40 -m "0fni" img.jpg --save-img .
```

I used `[i,n,f,0]` as the characterset since that's one of my aliases, and saved the colored output for use.