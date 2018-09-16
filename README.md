linux-kernel
===

My journey to linux kernel.

# Reference

[Kernel newbies](https://kernelnewbies.org)

[kernel doc](https://www.kernel.org/doc/html/latest)

Linux Kernel Development,3rd Edition

# Checkout linux kernel source code

[Linux kernel source tree](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git)

Source repository
git://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git

```
make submodule
```

# Build linux kernel

```
sudo apt-get install libncurses5-dev gcc make git exuberant-ctags bc libssl-dev bison flex libelf-dev

uname -r
cd linux && git checkout 4.16
cp /boot/config-`uname -r`* .config
```
