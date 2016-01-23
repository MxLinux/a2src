# a2src
Simple script for decompiling Android .APK files. 
Requires apktool and dex2jar, jadx optional (will be implemented soon).

## Features
- Creates .a2var in user home directory.
- Asks user for location of apktool/dex2jar binaries and sets them as variables in .a2var if not globally set.
- Decompiles an .apk file using apktool and dex2jar (required)

##### TODO:
- Support for jadx
