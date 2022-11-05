# tvh_patch
tvheadend patch für icam
- getestet auf debian 10/11 <br><br>
`sudo apt remove libdvbcsa-dev`<br><br>
`sudo apt install libdvbcsa1 i965-va-driver intel-media-va-driver libavahi-client3 libavahi-common-data libavahi-common3 libdrm-amdgpu1 libdrm-intel1 libdrm-nouveau2 libdrm-radeon1 libdvbcsa1 libllvm11 libpciaccess0 liburiparser1 libva-drm2 libva2 libx11-xcb1 libxcb-dri2-0 libxcb-dri3-0 libxcb-present0 libxcb-sync1 libxcb-xfixes0 libxshmfence1 libz3-4 mesa-va-drivers va-driver-all`<br><br>
`wget https://github.com/horschte/tvh_patch/raw/main/tvheadend_4.3-2049~g1a437c88e-dirty_amd64.deb`<br><br>
`wget https://github.com/horschte/tvh_patch/raw/main/libdvbcsa.so.1.0.1`<br><br>
`sudo cp libdvbcsa.so.1.0.1 /usr/local/lib/`<br><br>
`sudo cp libdvbcsa.so.1.0.1 /usr/lib/x86_64-linux-gnu/`<br><br>
`sudo dpkg -i tvheadend_4.3-2049~g1a437c88e-dirty_amd64.deb`<br><br>


