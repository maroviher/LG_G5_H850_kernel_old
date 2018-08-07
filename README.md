Linux kernel for G5 H850 International 
Forked form: https://github.com/stendro/msm8996_lge_kernel

Removed:
*module signing
*printk

Added:
charge control, see commit: 7f026b1a80c7d2e8769de5c9960af343ac919671

To build run: ./build.sh H850 && ./copy_finished.sh
