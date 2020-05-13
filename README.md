# tiny6410-uboot-2010.09
基于官方uboot-2010.09移植到目标版tiny6410，并且支持向内核传递设备树，
当执行bootm kernel_addr时采用向内核传递cmdline的方式启动内核
当执行bootm kernel_addr - dt_addr时向内核传递设备树的方式启动内核
