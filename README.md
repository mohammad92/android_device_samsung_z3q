## Recovery Device Tree for the Samsung Galaxy S20 Ultra 5G (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_z3q-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_sm8250
