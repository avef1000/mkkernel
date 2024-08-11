NEW TOOL: MKKERNEL - Extract Boot and Recovery Images with Ease!

Hey all,

I’m excited to introduce a brand-new tool called MkKernel, a powerful utility designed to extract kernel and ramdisk information from your boot and recovery images with a single command! Developed and built by yours truly, Avraham Freeman, this tool is written in C to ensure efficiency and speed.
What Does MkKernel Do?

MkKernel is your go-to tool for extracting critical information from boot and recovery images. With it, you can:

    Extract the kernel: Pull out the kernel from your boot or recovery image and save it for further analysis or modification.
    Extract the ramdisk filesystem: Unpack the entire ramdisk, regardless of its compression type (.gz, .lz4, etc.), into a directory for easy inspection.
    View detailed boot.img info: Print out all the important information about your boot image, including kernel size, ramdisk size, and much more!

Usage

Using MkKernel is super simple:

bash

sudo ./mkkernel <boot.img> or <recovery.img>

Just provide the path to your boot or recovery image, and MkKernel will handle the rest!
Coming Soon in Version 2!

Please note that the repack_boot_img feature is currently under development. This feature will allow you to repack the ramdisk and kernel back into a boot image, making custom kernel development and testing even easier. As of yet it will only work with the mkbootimg binary in the same directory, Stay tuned for Version 2, where this functionality will be fully implemented!

Support

If you find this tool useful, please consider supporting me on Cashapp at $blackwiddow987. Your support helps me continue developing and improving tools like MkKernel.

Catch the wave of the future in Android development with MkKernel – where power meets simplicity!

Cheers,
Avraham Freeman
- code_daemon
