## NOTES:

>***Due to the overuse of script, a bunch of APIs have been taken offline. It is okay if you do not receive all the messages***
> ***Termux version from Play Store is not supported since 2019, please use the latest version from F-Droid Store!
Download Now:  https://f-droid.org/packages/com.termux/  ***

## Compatibility
Check your Python version by typing in
```shell script
$ python --version
```
If you get the following
```shell script
Python 3.8.3
```
## Features

- Over 15 integrated messaging and calling APIs included with JSON
- Unlimited (with abuse protection) and super-fast bombing with multithreading

## Usage:

### Install from GIT

#### NOTE 

Git installation methods are not universal and are likely to differ between distributions so installing Git as per the given instructions below may not work. Please check out how to install Git for your Linux distribution [here](https://git-scm.com/). Commands below provide instructions for Debian-based systems.

>Running `SMSBOMB.sh` as sudo miscofigures files ownership. It is recommended not to run it as sudo

Run these commands to clone and run SMSBOMB.

#### For Termux
***Download Termux: https://f-droid.org/packages/com.termux/
***
To use the bomber type the following commands in Termux:
```shell script
apt update && apt upgrade
apt Instal curl
pkg install git -y 
pkg install python -y 
git clone https://github.com/WHITEDH4CKER/SMSBOMB.git
cd SMDBOMB
chmod+x SMSBOMB.sh
./SMSBOMB.sh
```

#### For iSH

To use the application, type in the following commands in iSH.
```shell script
apk add git
apk add python3
apk add py3-pip
apk add ruby
gem install toilet
git clone https://github.com/WHITEDH4CKER/SMSBOMB.git
cd SMSBOMB
pip3 install -r requirements.txt
chmod +x SMSBOMB.sh
./SMSBOMB.sh
```

#### For Debian-based GNU/Linux distributions

To use the application, type in the following commands in GNU/Linux terminal.
```shell script
sudo apt install git
git clone https://github.com/WHITEDH4CKER/SMSBOMB.git
cd SMSBOMB
chmod +x SMSBOMB.sh
bash SMSBOMB.sh
```

#### For MacOS

To use the application, type in the following commands in MacOS terminal:

##### Install via Homebrew

```shell script
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
````

##### Install dependencies:

```shell script
brew install git
brew install python3
sudo easy_install pip
sudo pip install --upgrade pip
git clone https://github.com/WHITEDH4CKER/SMSBOMB.git
cd SMSBOMB
bash SMSBOMB.sh
,,,

### TODO:

- [x] Make Code More Readable and Extensible
- [ ] Add More Mail Spam APIs
- [ ] Add More SMS Spam APIs
- [ ] Add More Call Spam APIs
- [ ] Resolve threading issue in some devices

## FAQ

**Q:** Is there any TBomb Website/App ?

**A:** There is no official website/app yet.The only official releases of TBomb are published in [Github](https://github.com/WHITEDH4CKER/SMSBOMB.git)
##
**Q:** Poor Internet Connection Detected:

**A:** Here are a few stuff you can try:
- Check your connection.
- Make sure `openssl` is installed.
- Try to `ping` any remote site/address to be sure.
- Try to reinstall if nothing works.
##
**Q:** Do you support "X" Country?

**A:** Most Countries are supported for SMS and only India for calls. The SMS delivery rate might be different for different countries.
##
**Q:** Can you add support for "X" Country?

**A:** We do what we can, but we cannot promise. Please stay tuned for future support. If you are ready to help then maybe we can do faster.
##
**Q:** Why is the limit so low?

**A:** Due the amount of requests, the APIs can die. To prevent a bigger outtake of TBomb, it has been limited. 
##
**Q:** Help, I got the error that the requirements aren't installed, even when the installer has successfully reached the main menu

**A:** First, make sure `python3` and `pip3` are installed. 
- The Easy Method:  
   `pip3 install tbomb`  
    Then execute by simply running `tbomb`
- The Git Method:  
    Clone the repo and Switch to the TBomb Directory and execute this command:  
    `pip3 install -r requirements.txt`
##
**Q:** Help, It says `command 'tbomb' not found` after installing PIP version!

**A:** Try running `sudo pip3 install tbomb`
##
**Q:** Help, I can't execute TBomb.sh!

**A:** Run TBomb Directly with `python3 bomber.py`
##
**Q:** Should I use VPN? 

**A:** No, If you are facing high fail rate as TBomb can fail due the high response time or API restrictions.
##
**Q:** How to get protection ?

**A:** Use OTP blockers and activate DND.
##
**Q:** Why does it fail?

**A:** Due to the overuse of script, a bunch of APIs have been taken offline. It is okay if you do not receive all the messages.
##
### Support

For Queries: [Telegram](t.me/mranonymous4u)  

<p align="right"> Last FAQ Update: 08.08.2023 </p>
