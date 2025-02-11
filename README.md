
pour faire build edgetx:

info tiré de : https://github.com/EdgeTX/edgetx/wiki/Building-radio-firmware-in-a-webbrowser-with-Gitpod
options: https://github.com/EdgeTX/edgetx/wiki/Compilation-options



[
https://gitpod.io/#https://github.com/edgetx/edgetx/tree/...


cmake -Wno-dev -DPCB=X7 -DPCBREV=MT12 -DDEFAULT_MODE=2 -DCMAKE_BUILD_TYPE=Release ../

make arm-none-eabi-configure

make -C arm-none-eabi -j`nproc` firmware

cd arm-none-eabi
mv firmware.bin edgetx_mt12_3d1e7a9_6_dec_2024.bin
](https://gitpod.io/#https://github.com/edgetx/edgetx/tree/2b920a014b0d69684eecfc20a74855d8b553e005


cmake -Wno-dev -DPCB=X7 -DPCBREV=MT12 -DDEFAULT_MODE=2 -DCMAKE_BUILD_TYPE=Release ../

make arm-none-eabi-configure

make -C arm-none-eabi -j`nproc` firmware

cd arm-none-eabi
mv firmware.bin edgetx_mt12_2b920a0_22_dec_2024.bin




https://gitpod.io/#https://github.com/edgetx/edgetx/tree/2b920a014b0d69684eecfc20a74855d8b553e005


cmake -Wno-dev -DPCB=X7 -DPCBREV=MT12 -DDEFAULT_MODE=2 -DCMAKE_BUILD_TYPE=Release ../

make arm-none-eabi-configure

make -C arm-none-eabi -j`nproc` firmware

cd arm-none-eabi
mv firmware.bin edgetx_mt12_2b920a0_22_dec_2024.bin



https://gitpod.io/#https://github.com/edgetx/edgetx/tree/795cc35b8d357825944665f99d824f9c4cd0ca28


cmake -Wno-dev -DPCB=X7 -DPCBREV=MT12 -DDEFAULT_MODE=2 -DCMAKE_BUILD_TYPE=Release ../

make arm-none-eabi-configure

make -C arm-none-eabi -j`nproc` firmware

cd arm-none-eabi
mv firmware.bin edgetx_mt12_2b920a0_15_jan_2025.bin


https://gitpod.io/#https://github.com/edgetx/edgetx/tree/d9f4667cfd410a7124c9765719a55a679a25d96b


cmake -Wno-dev -DPCB=X7 -DPCBREV=MT12 -DDEFAULT_MODE=2 -DCMAKE_BUILD_TYPE=Release ../

make arm-none-eabi-configure

make -C arm-none-eabi -j`nproc` firmware

cd arm-none-eabi
mv firmware.bin edgetx_mt12_d9f4667_21_jan_2025.bin






)
