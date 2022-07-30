<img src="https://github.com/Genymobile/scrcpy/raw/master/app/data/icon.svg" width="128" height="128" alt="scrcpy" align="right" />

## emulator android on mac
- [x] macos controller on keyboard and touchpad
- [x] smooth screen on macos on mobile
- [x] input text eng
- [ ] input text th
- - -

<img width="1440" alt="Screen Shot 2565-07-30 at 16 09 35" src="https://user-images.githubusercontent.com/73060136/181903822-f4dc320e-aefd-4759-995e-e90ed3c30bf4.png">

<h5 align="center"> - error when input thai text - </h5>

- - -
### 😵‍💫 EXAM

ส่งภาพและเสียงมือถือเข้าคอม ไม่กระตุก Full HD ใช้ USB ต่อตรง ด้วย scrcpy + sndcpy ฟรี!!
- https://www.youtube.com/watch?v=lEknczHL6qg

Mirror Android screen to Mac or PC with SCRCPY | Better than Vysor and AirDroid
- https://www.youtube.com/watch?v=KPwackgViyE 

```bash
# src 
# https://github.com/Genymobile/scrcpy

# dowload
brew install scrcpy
brew install android-platform-tools
# run
scrcpy
```
- - -

### 😵‍ BUG
```bash
# ไม่สามารถพิมภาษาไทยได้
# input: สวัสดี , res: ⬇⬇
[server] WARN: Could not inject char u+0e17
[server] WARN: Could not inject char u+0e44
[server] WARN: Could not inject char u+0e33
[server] WARN: Could not inject char u+0e17
[server] WARN: Could not inject char u+0e1f
[server] WARN: Could not inject char u+0e2b
[server] WARN: Could not inject char u+0e01
[server] WARN: Could not inject char u+0e1f
```

- - -

### 😵 DOING

Fixed char

Same problem </br>
[Non english keyboard layout #37](https://github.com/Genymobile/scrcpy/issues/37) </br>
[Can you support PC typing to mobile phone in Chinese? #632](https://github.com/Genymobile/scrcpy/issues/632)

Tool </br>
[SocketIME](https://github.com/npes87184/SocketIME) </br>
[ADBKeyBoard](https://github.com/senzhk/ADBKeyBoard)
- - -

