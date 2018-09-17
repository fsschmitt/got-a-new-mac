#  gotAnewMac
Automatically installs all the Apps a designer needs on your brand new Mac

## 💾 Download this repository.

## 💻 Installation
- Open `Brewfile` with TextEdit and make sure to comment out all the Apps you don't want
- Open Terminal app.
- Type `CD ` (with a space) and drag the `gotAnewMac` folder to the Terminal app.
- Hit [ENTER ↵].
- Type: `. install.sh` (don't forget the `.` before install) followed by [ENTER ↵]. (At this point, OSX might ask you to install the Xcode terminal tools, if so, rerun `. install.sh` once done)
- Follow the instructions in the terminal. **You will be prompted for your appleID and your system password later**

## 📂 Alternative `Applications` folder location
If you prefer to have your apps in `/YourUser/Applications`, open `install.sh` with TextEdit
and uncomment the line `export HOMEBREW_CASK_OPTS="--appdir=~/Applications"`.
