# init_emu

If you want to understed why i made this script, I worte an post in my blog explaining this, feel free to check it out!
https://gabrielpolastrini.com/blog/posts/init_emu.html


*This script is configured with the Pixel 2 emulator. If you don't have the Pixel 2 emulator, the script won't work.
If you want to change the emulator, edit the line ```emulator @ Pixel_2``` with the emulator you have installed.

## usage

add this to lines into your .bashrc:

```
export ANDROID_HOME=$HOME/Android/Sdk
```

```
export PATH=$PATH:$ANDROID_HOME/tools
```
clone the repository into yout home dir:

```
cd ~
```

```
git clone https://github.com/rootgp/init_emu.git
```

```
cd init_emu
```
move the script to your home directory

```
mv init_emu.sh ~
```

give execution permissions to the script:

```
chmod +x init_emu.sh
```
and intialize it:

```
./init_emu.sh
```
