# How to improve your performance on the Playstation 4

## This page will only cover the Playstation Fat and Slim because the Pro has basically no issues in terms of running Window managers or Desktop environments.
>- **NOTE: All of the changes to the Playstation 4 Fat or Slim can be applied to the Pro if you want to squeeze in more performance**


# 1 - Kernel level optimizations

- Most of the optimizations for the kernel can not be applied after installation so to use this visit the [How to compile your own kernel page](https://flyingphantom.github.io/ps4-linux-tutorial/kernel.html).

| Kernel optimizations           | What this option does?      
|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| _processor_opt="btver2"	 | Applies microarcitecture specific optimizations to the kernel.																		  |
| _cpusched="bmq"		 | Uses bmq as the default scheduler, way better then the default one and usually most present in the newer kernel versions.											  |
| _lto_mode="thin"		 | Uses Thin LTO mode to optimize for performance.**(SHOULD NOT BE USED WITH LLVM BECAUSE IT CAN LEAD TO UNBOOTABLE KERNEL)**.											  |
| _compileroptlevel="1"		 | Uses compiler to optimize for performance.																					  |
| _tcp_cong_alg="bbr"		 | Uses a better network algorithm that could have better network stability or speed. ***Small Note: even if this does not change anything internet will still work properly***.				  |
| _default_cpu_gov="ondemand"	 | Makes the default cpu governor "ondemand" meaning it uses more power when needed resulting in quieter experience.												  |
| _aggressive_ondemand="true"	 | Makes the "ondemand" governor more aggressive.																				  |
