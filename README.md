
pour faire build edgetx:

info tiré de : https://github.com/EdgeTX/edgetx/wiki/Building-radio-firmware-in-a-webbrowser-with-Gitpod
options: https://github.com/EdgeTX/edgetx/wiki/Compilation-options




https://gitpod.io/#https://github.com/edgetx/edgetx/tree/...


cmake -Wno-dev -DPCB=X7 -DPCBREV=MT12 -DDEFAULT_MODE=2 -DCMAKE_BUILD_TYPE=Release ../

make arm-none-eabi-configure

make -C arm-none-eabi -j`nproc` firmware

cd arm-none-eabi
mv firmware.bin edgetx_mt12_3d1e7a9_6_dec_2024.bin
