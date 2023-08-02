# itat-mobile-android-studio
Sebelum Memulai lakukan Installasi
1. installasi Android Studio :
 ```sh
  https://developer.android.com/studio/install?hl=id
```
2. Installasi Git
 ```sh
  https://www.nesabamedia.com/cara-install-git-di-windows-10/
```

# Konfigurasi
1. Lakukan pengambilan source code pada git dengan perintah
 ```sh
git clone https://github.com/logika-pratama911/itat-mobile-android-studio.git
```
2. Open Android studio
   Pilih File > Open > itat-mobile-android-studio (folder project itat-mobile-android-studio)
3. Sesuaikan SDK compailSdk 33 dan targetSdk 33 pada build.gradle
4. Tools > SDK Manager >  (Sesuaikan SDK Tools  33.0.1 dan SDK plaform Android)
5. Installasi WebServer dan konfigurasi itat-mobile web
```sh
https://github.com/logika-pratama/Web_ITAT
```      
7. Sesuaikan URL dimana aplikasi ITAT hosting pada MainActivity.java (jika ada perubahaan)
```sh
webView.loadUrl("https://10.230.200.157/itat");
``` 
5. Lakukan build apk
   Build > Build Bundle(s) / APK(s) > Build APK(s)
