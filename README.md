<h1 align="center">
        <img height="60%" width="50%" src="mophun_logo.png"><br>
</h1>

# Mophun

| Emulators                       | Version     | Latest Version | Active |
| ------------------------------- | ---------- | -------------- | -------- |
| mophun-mod <small>(tuxality-mod)</small> | 2.5.4 Alpha 2   | ![pic](Logos/Windows.png) | Yes (tuxality-mod only)
| 4mophun          | 1.1 | ![pic](Logos/WinMobile.png) | No |
| mophun games launcher  | 1.01/1.04 unsigned | ![pic](Logos/Symbian.png) | No |

**mophun** is an official Mophun emulator. It was created by Synergenix Interactive, the creators of Mophun, for the Mophun SDK (latest version 2.5). It was designed for development and demos.

### Changelogs

**2.5.4**

- Updated profile for Model 16 (Archos Gmini 400) including skin
- Data certificate bugfix for category 1 and 2 profiles (when using DataCertificateTestSuite for example)

**2.5.3**

- New profiles added for Symbian devices
- New preliminary profiles for unnamed jukeboxes (Model 14 & 16). No timing!
- Updates to the 3D API, see the SDK release notes
- 3D bugfix in P800/P900 profiles

**2.0.3**

- Make it possible to enable/disable onscreen joystick on P800/P900. All it does is change the screen size, it does not draw the panel.
- In models 1,2 and 5 (SonyEricsson T300 and T610 variants) use windows fonts as a fallback if a requested character does not exist in the SonyEricsson device font (i.e chinese).

**2.0.2**

- profile for GameTrac added (no timing yet)
- Added interpolation for 16bit

**2.0.1**

- Help file for emulator added

**2.0.0**

- S60 profiles split up into 7650, 3650 and N-Gage profiles
- Additional 3D features

# mophun-mod (Tuxality mod)
An unofficial mod, created by Tuxality, boots encrypted games without the need to decrypt them first by decrypting them on the fly.

### Changelogs

**Alpha 2**
- Drag and drop support is added, minor issues are fixed (e.g. "Compressed MPN file is not supported yet!" is corrected to "Compressed MPN files are not supported yet!") and debug messages due to failure (decryption or source files) are implemented. Planned for the next version, A3 (alpha 3), are decompression, Symbian/Pocket PC key fallback and to run as early as Windows 98, just like the unmodified version.

**Alpha 1**
- Decryption only works if opening from the Open menu. However, compressed games are detected, but cannot run. Instead, an error saying "Compressed MPN file is not supported yet!" appears. Additionally, there may be some cases of crashing and the date, time, profile stuff is not properly set or selected

# Mophun Games Launcher
**Mophun Games Launcher** only compatible with 15 games, all of which use the 3D engine and were released for Symbian.

<code>
English [1.0/1.02/1.04 unsigned/BinPDA - 7/8/9 series]
Russian [Blaze mod - N-series Edition]
Chinese [S60V3]
</code>

*Included games:*

- Anarchy Boxing 3D 1.60
- Carmageddon 3D
- The Da Vinci Code 1.0.2
- Fatal Arena
- Football Pro Contest 1.0.4
- Golf Pro Contest 1
- Golf Pro Contest 2 1.0.1
- Heli Attack 2
- Joe ’s Treasure Quest
- Lock ‘n Load Combat Arena 1.20.0
- Lock ‘n Load Rise of War 1.01
- Lock ‘n Load 2 1.1.0
- Martial Arts 3D 1.0
- Rally Pro Contest 3D 1.30
- Worms World Party

<code>EKA2L1/data/drives/e/data/mp/f0001092</code>

# 4mophun 

<h1 align="center">
        <img height="60%" width="50%" src="Extra/4mophun.jpg"><br>
</h1>

**4mophun** on Windows Mobile, you can run 4mophun on Windows through Microsoft's Device Emulator. Does not work with games that are locked (e.g. have a predefined IMEI recognition algorithm) or do not use the 3D engine.

*Compatibility list:*

| Name        | Code name           | Status |
| ------------- |:-------------:| -----:|
| American Racing 3D      |  |  |
| Anarchy Boxing 3D      | RealBoxing | Work |
| Carmageddon 3D      | Carmageddon3D      |   Work |
| Da Vinci Code | DVC      |    Work |
| Fatal Arena | FA3D      |    Work |
| Football Pro Contest | FootballPro      |    Work |
| Golf Pro Contest | GolfProContest      |    Work with no sound + some backgrounds are 176x208|
| Golf Pro Contest 2 | GolfProContest2      |    Work with no sound |
| Heli Attack 2      |  |  |
| Joes Treasure Quest 3D      |  |  |
| Lock'n Load: Rise of War | LocknLoad      |    Work |
| Lock'n Load 2 | Exile      |    Work |
| Lock'n Load: Combat Arena | ArenaTMN      |    Work but only multiplayer |
| Martial Arts 3D | MA3D      |    Work |
| Rally Pro Contest | RallyProContest      |    Work |
| Worms World Party | WormsWWP      |    Not work with bad or missing certificate |

### Screenshots

|     |     |
| --- | --- |
| ![Screenshots](Screenshots/2.jpg) | ![Screenshots](Screenshots/3.jpg) |
| ![Screenshots](Screenshots/6.jpg) | ![Screenshots](Screenshots/11.jpg) |
| ![Screenshots](Screenshots/14.jpg) | ![Screenshots](Screenshots/4.jpg) |
| ![Screenshots](Screenshots/5.jpg) | ![Screenshots](Screenshots/7.jpg) |
| ![Screenshots](Screenshots/8.jpg) | ![Screenshots](Screenshots/10.gif) |
| ![Screenshots](Screenshots/12.jpg) | ![Screenshots](Screenshots/13.jpg) |
| ![Screenshots](Screenshots/15.jpg) | ![Screenshots](Screenshots/16.gif) |
| ![Screenshots](Screenshots/17.jpg) | ![Screenshots](Screenshots/18.jpg) |
| ![Screenshots](Screenshots/19.gif) | ![Screenshots](Screenshots/20.jpg) |
| ![Screenshots](Screenshots/21.png) | ![Screenshots](Screenshots/22.png) |

### mophun SDK
[Mophun SDK 2.5](http://tuxality.net/public/MophunSDK_2_5.zip)
