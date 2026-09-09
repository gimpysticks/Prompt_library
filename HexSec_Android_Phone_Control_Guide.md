# Control Your Android Phone from Your PC

**Source:** HexSec Community carousel

**Transcription note:** Commands are preserved as shown in the supplied
images. Decorative/background terminal text is omitted unless it
contributes to the instructions.

## 1. Your PC Can Take Over Your Phone

**USB • Wi-Fi • Remote Screen • Real Commands**

**Swipe to learn how**

## 2. What You'll Learn

1.  Connect phone to PC
2.  Mirror the screen
3.  Take remote control
4.  Use commands like a pro
5.  USB setup
6.  Wireless setup
7.  Useful scrcpy commands
8.  iPhone options

*From first connection to real remote control.*

## 3. Step 1 --- Prep Your Android

1.  Install ADB platform tools
2.  Install scrcpy
3.  Enable Developer Options
4.  Enable USB Debugging
5.  Authorize the PC

### Essential Commands

``` bash
adb version
```

Check ADB installation.

``` bash
scrcpy --version
```

Verify scrcpy is installed.

``` bash
adb devices
```

Confirm the phone is detected.

## 4. Step 2 --- Take Control via USB

### 01 --- Detect connected phone

``` bash
adb devices -l
```

### 02 --- Open live remote screen

``` bash
scrcpy
```

### 03 --- Select USB device

``` bash
scrcpy -d
```

### 04 --- Target a specific device

``` bash
scrcpy -s SERIAL
```

**Fast • Stable • Instant Control**

## 5. Step 3 --- Go Wireless

### 01 --- Pair the phone

``` bash
adb pair IP:PAIR_PORT
```

### 02 --- Connect over Wi-Fi

``` bash
adb connect IP:PORT
```

### 03 --- Verify connection

``` bash
adb devices
```

### 04 --- Launch wireless control

``` bash
scrcpy -e
```

### 05 --- Disconnect when done

``` bash
adb disconnect
```

**No cable needed.**

## 6. Power Commands

### 01 --- Switch to TCP/IP mode

``` bash
scrcpy --tcpip
```

### 02 --- Control with screen off while keeping device awake

``` bash
scrcpy --turn-screen-off --stay-awake
```

### 03 --- Record the session to video

``` bash
scrcpy --record=session.mp4
```

### 04 --- Display touch points on screen

``` bash
scrcpy --show-touches
```

### 05 --- Improve keyboard input handling

``` bash
scrcpy --keyboard=uhid
```

**Control • Record • Optimize**

## 7. Control It Like a Pro

-   **MOD + H** = Home
-   **MOD + B** = Back
-   **MOD + S** = App Switcher
-   **CTRL + drag** = Pinch / zoom
-   **MOD + P** = Power
-   **MOD + O** = Turn screen off
-   **MOD + V** = Paste clipboard

**Your keyboard becomes your phone controller.**

## 8. More Than Screen Control

### Send files

``` bash
adb push file.zip /sdcard/Download/
```

### Pull files

``` bash
adb pull /sdcard/file.zip .
```

### Install APK

``` bash
adb install app.apk
```

### Take screenshot

``` bash
adb exec-out screencap -p > screen.png
```

### Record screen

``` bash
adb shell screenrecord /sdcard/demo.mp4
```

**Files • Apps • Capture**

## 9. What About iPhone?

**Yes --- but differently.**

### Mac + iPhone Mirroring

-   View and interact
-   Use keyboard and mouse
-   Manage notifications

### CLI Tools

List connected devices:

``` bash
idevice_id -l
```

Read device information:

``` bash
ideviceinfo
```

Capture a screenshot:

``` bash
idevicescreenshot
```

Perform device backup tasks:

``` bash
idevicebackup2
```

**iPhone control is not the same as scrcpy.**

## 10. Recap

-   USB control
-   Wireless control
-   Pro scrcpy commands
-   Shortcuts
-   Files and screenshots
-   iPhone options

**Now you know how to take control.**
