# DART-SD410-lk
Bootloader for var-dartsd410

# Clone this bootloader
# Install arm-eabi-gcc prebuilt binary and add to path
git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.8
PATH=./arm-eabi-4.8/bin:$PATH

# Compile the bootload
cd DART-SD40-lk
make msm8916
