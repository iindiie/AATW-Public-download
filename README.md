# Globe Trek - Discovering Angela

## Windows (the PC that runs the globe)

**[Download the Windows installer](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Setup.exe)** (version 1.4.0, about 28 MB)

Run the installer. No admin rights are needed. If Windows SmartScreen appears, choose **More info**, then **Run anyway**, because the installer is not code signed. When Windows asks whether Globe Trek may use the network, allow it on **Private networks** so the phone app can reach it.

SHA-256: `95ca4a3038dbea62c0ab390b16bcf43a3da2aa2e144fc70341a4703ee8f64770`

## Mac

Not sure which Mac you have? Apple menu, **About This Mac**: "Chip: Apple M..." means Apple Silicon.

| | Disk image | Zip (if the disk image will not open) |
|---|---|---|
| Apple Silicon (M1 to M4 and later) | [GlobeTrek-AppleSilicon.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.dmg) | [GlobeTrek-AppleSilicon.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.zip) |
| Intel | [GlobeTrek-Intel.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.dmg) | [GlobeTrek-Intel.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.zip) |

Disk image: open it and drag **Globe Trek** to **Applications**. Zip: open it, then drag the **Globe Trek** app it unpacks into **Applications**.

The app is not notarized by Apple, so the first time you open it macOS says it cannot verify it. Click **Done**, then go to **System Settings**, **Privacy & Security**, scroll down and click **Open Anyway** next to Globe Trek. The globe opens in Google Chrome or Microsoft Edge if one is installed, otherwise in your default browser. Quit Globe Trek from the Dock to stop it. Press **Option+M** for settings. Settings are kept in `~/Library/Application Support/Globe Trek`.

SHA-256: Apple Silicon dmg `fe03b4711e8f6c44bb55e7a70d572325ff12c38acb23c2470664b2d1e68fe29e`, zip `8d38aae0060b57065fcda04cba0cdfe77aecb16b9717c2201d89f4a3cc7f5236`  
SHA-256: Intel dmg `bcbc5e3405cbd2bb4703a241caa6b264dfbe74314744da5078a0db2e3270f00a`, zip `a510682f4dd98df7366f3f807ad5510f25579fb98880b1050240faa843096efe`

## Android (Angela's phone)

**[Download Globe Trek Remote for Android](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrekRemote.apk)** (version 1.2.0)

If an older Globe Trek Remote is installed, uninstall it first: this version is signed differently and will not install over it.

Open the downloaded file on the phone and allow installing from your browser when Android asks. Then, on the PC, press Ctrl+M (Option+M on a Mac), open **Mode**, and either tap **Scan QR code** in the app, or scan the QR code with the phone camera and the app opens by itself.

SHA-256: `011e1f933f20d5482b7705ffeca9cd82c8b15e6d84506dbe9491026402e39606`
