# dyld_shared_cache_util

Download the source here:

https://opensource.apple.com/tarballs/dyld/dyld-851.27.tar.gz

```
cd dyld-851.27
patch -s -p0 < dyld-851.27.patch
```

You'll now be able to build the `dyld_shared_cache_util` target from the Xcode project - hooray!

Thanks to [Jeff Johnson](https://twitter.com/lapcatsoftware) for his [post](https://lapcatsoftware.com/articles/bigsur.html) outlining how to do this.
