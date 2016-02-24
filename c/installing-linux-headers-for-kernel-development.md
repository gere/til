# Installing Linux headers for kernel development

At least you need headers like <linux/kernel.h> or <linux/init.h> to develop modules if you don't want to download the full source. 
Run the following:
```bash
$ sudo apt-get update
$ sudo apt-get install linux-headers-$(uname -r)
```