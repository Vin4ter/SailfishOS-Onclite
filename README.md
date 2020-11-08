# SailfishOS | Redmi | 7/y3
installation:
1) Flash Leneage os 16 "https://www.androidfilehost.com/?fid=4349826312261670404"
2) Unpacking sailfish-3.2.0.12-onclite.zip to internal storage (/sdcard/sailfish_unzip) 
3) In OFRP(orange fox recovery project) terminal and adb shell write
    
    rm -rf /data/.stowaways/sailfishos/
    mkdir -p /data/.stowaways/sailfishos
    /sdcard/sailfish_unzip/sailfish_onclite_3.2.0.12_Simondvic.tar.bz2 -C /data/.stowaways/sailfishos/

4)No boot
    
