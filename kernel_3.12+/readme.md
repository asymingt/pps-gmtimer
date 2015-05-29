cd /path/to/kernel/source/tree
for i in /path/to/patches/*.patch; do patch -p1 < $i; done
