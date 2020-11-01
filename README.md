# Notes

We have 5 major device sizes to worry about:

- mobile portrait
- mobile landscape
- tablet portrait
- tablet landscape
- laptop

Those devices map to those pixel values:

- mobile portrait: less than 640px
- mobile landscape: > 640px
- tablet portrait: > 768px
- tablet landscape: > 1024px
- laptop: > 1280px

## Min-Width

```css
    @media only screen and (min-width: 600px)  {...}
```

What this query really means, is “If [device width] is **greater than or equal** to *600px*, then do {…}”

## Max-width

```css
@media only screen and (max-width: 600px)  {...}
```

What this query really means, is “If [device width] is **less than or equal** to *600px*, then do {…}”

### References

1. [Media Queries Demystified: CSS Min-Width and Max-Width](https://www.emailonacid.com/blog/article/email-development/emailology_media_queries_demystified_min-width_and_max-width/)