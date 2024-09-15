adb shell
SU
resetprop ro.bootmode usbradio
resetprop ro.build.type userdebug
setprop sys.usb.config diag,diag_mdm,adb
diag_mdlog

imei pixel 5 355660112660784
catatan : 
install configuration di qualcomm driver semaunya install
kalo ada yg disuruh restart, ya.
root dulu sebelum melakukan suntik imei



ketika melakukan diag_mdlog jangan dulu di cabut
hingga muncul createnewfile disitu bakalan stuck tekan ctrl + c
kemudian ubah pengisi daya ke transfer file