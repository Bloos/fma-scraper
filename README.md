The website has changed and the old fma-scraper project is now broken. I've fixed it, but I cannot guarantee correctness and stability. I'm putting it here because the original project is archived and cannot be updated.

# Free Music Archive scraper
High-performance scraper for https://freemusicarchive.org

 << https://github.com/terorie/fma-scraper >>

Please don't put unnecessary load on their servers.
Mirror at https://archive.org/details/freemusicarchive

```
Usage:
  -c, --concurrency uint   Number of concurrent downloads (default 4)
  -g, --genre string       Genre to archive
      --list-genres        Print a list of genres
      --min-page uint      Starting page (default 1)
  -o, --out-dir string     Output directory (default "Downloads")
      --page-size uint     Page size (default 500)
  -v, --verbose            More output
```
