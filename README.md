# render_boost
Speedup page delivery by caching render based on checksum.

This module require kernel patch.
```
cd document_root/sites/all/modules/
git clone https://github.com/itpatrol/render_boost.git
cd ../../../
cat sites/all/modules/render_boost/render_boost.patch| patch -p1
```
