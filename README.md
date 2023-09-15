# Document-Flutter
![App Screenshot](https://firebasestorage.googleapis.com/v0/b/nhuandev-1c4d9.appspot.com/o/image_2023_09_15T02_39_45_211Z.png?alt=media&token=3e741f4e-65d2-4a52-bba1-b6b756c6aaa2)

## LINK

 - [Conver Json To Dart]([https://awesomeopensource.com/project/elangosundar/awesome-README-templates](https://app.quicktype.io/))

## TERMINAL

Remote and Update Pod
```bash
rm pubspec.lock && \                                                                                                                                                                                                          
flutter clean && \
cd ios && \
pod cache clean --all && \
cd .. && \
flutter pub get && \
cd ios && \
pod update && \
cd ..
```
Chuyển môi trường Flutter
```bash
export PATH=/Users/dtu/development/tools/flutter/bin:$PATH
echo $PATH
```
Chuyển certificate
```bash
flutter config --clear-ios-signing-cert
```
Chạy Flavor
```bash
flutter pub run flutter_flavorizr -p google:firebase
```
## Support

For support, email nhuandevmobile@gmail.com or join our Slack channel.
