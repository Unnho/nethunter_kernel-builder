# Kali NetHunter Kernel Builder

<!--![Kali NetHunter](https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/raw/master/images/nethunter-git-logo.png)-->

## Installation

Clone this repository into your kernel source tree, e.g.

``` bash
cd android_kernel_oneplus_sm8150/
git clone https://github.com/Unnho/nethunter_kernel-builder.git builder
```

**cd** into `builder/`, open `config` and make sure that you are happy with all the settings.

Important: Changes should not be made in this file. Copy it accross to `local.config` and delete everything except the parameters you would like to change. Change those parameters and save it.

The settings in `local.config` overwrites `config` but will itself not be overwritten by updates.


Saturday 4:25 pm, 4 November 2023 (IST)
