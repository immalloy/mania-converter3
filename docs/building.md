# Building Mania Converter
1. Install [**haxe**](https://haxe.org)
2. Do these commands in cmd:
```
haxelib install hxcpp 4.3.2
haxelib install lime 8.0.2
haxelib install openfl 9.2.2
haxelib install flixel 5.3.1
haxelib install flixel-tools 1.5.1
haxelib install flixel-ui 2.5.0
haxelib install flixel-addons 3.1.1
haxelib run lime setup
haxelib run lime setup flixel
haxelib run flixel-tools setup
```
### If you not on Windows go to step 6
3. Download [**VS Community**](https://visualstudio.microsoft.com/downloads/)
4. Open it and go to Individual Components tab
5. Download these libs:
```
MSVC v142 - C++ x64/x86 build tools
Windows SDK
```
6. And now compile it with: `lime test <windows/linux/mac>`
7. After compilation, keep the `lime.ndll` file in the same directory as the `ManiaConverter` executable. Removing it will lead to the startup error "Could not load module lime@lime_application_create__prime".
