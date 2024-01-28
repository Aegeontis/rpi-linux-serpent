# rpi-linux-serpent
Raspberry pi kernels with serpent cryptography support

# What this does
1. Check daily if there has been a new release in https://github.com/raspberrypi/linux
2. Build the kernel exactly the same way as the upstream repo + set `CONFIG_CRYPTO_SERPENT=m`
3. Package the kernel into a deb file
4. Host a deb repo with the kernel files

# How to use
1. tbd
