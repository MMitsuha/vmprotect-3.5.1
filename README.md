# How to build VMProtect for Mac
1.You need a Mac 

2.Make sure you have Xcode,CommandLineDeveloperTools,Qt5 installed

3.Open `VMProtect/mac_gui.mak`, change `/Users/user/Qt/5.15.2/clang_64`  to your own Qt5 install dir

4.
```
cd core/invariant && make
cd ../ && make
cd ../VMProtectCon && make
cd ../VMProtect && make
```

5. The generated files will be in `bin/64`
6. Enjoy it

![mac.jpg](https://github.com/61bcdefg/vmprotect-3.5.1/blob/master/mac.jpg?raw=true)
