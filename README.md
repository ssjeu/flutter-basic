# Flutter Basic
## ๐ผ Why Flutter?
- ํฌ๋ก์ค ํ๋ซํผ ์ฑ(Cross Platform App): ํ๋์ ํ๋ก๊ทธ๋๋ฐ ์ธ์ด์ ์์ค์ฝ๋๋ก Android์ iOS๋ฅผ ๋ชจ๋ ๊ฐ๋ฐ<br/>
- ๊ตฌ๊ธ์์ ์ถ์ํ ์คํ ์์ค ๋ชจ๋ฐ์ผ ์ ํ๋ฆฌ์ผ์ด์ ํ๋ ์ ์ํฌ
- ๋์ ์์ฐ์ฑ๊ณผ React-native๋ณด๋ค ๋ฐ์ด๋ ์ฑ๋ฅ
- [Flutter ๊ณต์ ๋ฌธ์](https://docs.flutter.dev/)
<br/>

## ๐ How To Start (for MAC)
### ์ค์น ํ์ ํ๋ก๊ทธ๋จ 
- Flutter : Android์ iOS ์ฑ์ ํ๋์ ์ฝ๋๋ก ๊ตฌํํ  ์ ์๋๋ก ๋์์ฃผ๋ ํ๋ ์์ํฌ<br/>
- VSCode : ์ฝ๋๋ฅผ ์์ฑํ  ๋ ์ฌ์ฉํ๋ ์๋ํฐ<br/>
- Android Studio : Android ์ฑ์ ๊ฐ๋ฐํ๊ธฐ ์ํด ํ์ํ IDE. ์๋ฎฌ๋ ์ดํฐ ํฌํจ<br/>
- Xcode : iOS ์ฑ์ ๊ฐ๋ฐํ๊ธฐ ์ํด ํ์ํ IDE. ์๋ฎฌ๋ ์ดํฐ ํฌํจ<br/>
<br/>

1. Flutter ์ค์น
```
$ echo 'export PATH="$PATH:$HOME/development/flutter/bin"' >> ~/.zshrc && source ~/.zshrc
$ flutter --version
$ flutter doctor
```

2. VSCode Extension ์ค์น<br/>
- Extension ํญ์์ Flutter (Dart) ์ค์น
<br/>

3. Android Studio License ์ค์ 
```
$ flutter doctor --android-licenses
```

4. Xcode License ์ค์ 
```
$ sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
$ sudo xcodebuild -runFirstLaunch
```

### ์ ํ๋ก์ ํธ ์์ฑ
- View โ Command Palette (Cmd + Shift + P)
- Flutter: New Project โ Application
