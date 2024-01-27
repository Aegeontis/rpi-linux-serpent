# rpi-linux-serpent
Raspberry pi kernels with serpent cryptography support

# What this does
1. Check daily if there has been a new release in https://github.com/raspberrypi/linux
2. Run the same code as https://github.com/raspberrypi/linux/blob/rpi-6.1.y/.github/workflows/kernel-build.yml + `scripts/config --file ${{github.workspace}}/build/.config --set-val CONFIG_CRYPTO_SERPENT y`
3. Package the kernel into a deb file
4. Host deb repo with the kernel files

# How to use
1. Add repo to your system
2. tbd
