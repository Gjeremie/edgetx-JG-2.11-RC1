
**Pour faire build edgetx:**

info tiré de : https://github.com/EdgeTX/edgetx/wiki/Building-radio-firmware-in-a-webbrowser-with-Gitpod <br>
options: https://github.com/EdgeTX/edgetx/wiki/Compilation-options <br> <br>


**CODE: <br>**

https://gitpod.io/#https://github.com/edgetx/edgetx/tree/2b920a014b0d69684eecfc20a74855d8b553e005


cmake -Wno-dev -DPCB=X7 -DPCBREV=MT12 -DDEFAULT_MODE=2 -DCMAKE_BUILD_TYPE=Release ../

make arm-none-eabi-configure

make -C arm-none-eabi -j\`nproc\` firmware

cd arm-none-eabi <br>
mv firmware.bin edgetx_mt12_3d1e7a9_6_dec_2024.bin

 <br> <br>
**ou AUTRE CODE: <br>**

https://gitpod.io/#https://github.com/edgetx/edgetx/tree/2b920a014b0d69684eecfc20a74855d8b553e005

cd /workspace/edgetx-JG-2.11-RC1/

FLAVOR=mt12 tools/build-gh.sh
