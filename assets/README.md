# Convert PNG to WebP

Using Imagemagick.

## Lossless

```
mogrify -strip -format webp -define webp:lossless=true *.png
```

## Lossy compression

```
mogrify -strip -format webp -define webp:webp:method=6 *.png
```