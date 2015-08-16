# Huawei Y511-u30 source code 3.4.67
Build Command:

cd KK_huawei_y511 ./mk -o=TARGET_BUILD_VARIANT=user y511 n k

Then, to create the boot.img:

./pack_bootimage.sh

Work:
touchscreen
lcm (stripe top)
sound


Not working:
keypad (volume)
accelerometer
alsps
camera

