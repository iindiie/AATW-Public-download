# Globe Trek - Discovering Angela

## Windows (the PC that runs the globe)

**[Download the Windows installer](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Setup.exe)** (version 1.3.2, about 28 MB)

Run the installer. No admin rights are needed. If Windows SmartScreen appears, choose **More info**, then **Run anyway**, because the installer is not code signed. When Windows asks whether Globe Trek may use the network, allow it on **Private networks** so the phone app can reach it.

SHA-256: `cfba1cf97a0d094db53878038a9ce810dd0871d576f37a81b69fd2044854d305`

## Mac

Not sure which Mac you have? Apple menu, **About This Mac**: "Chip: Apple M..." means Apple Silicon.

| | Disk image | Zip (if the disk image will not open) |
|---|---|---|
| Apple Silicon (M1 to M4 and later) | [GlobeTrek-AppleSilicon.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.dmg) | [GlobeTrek-AppleSilicon.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.zip) |
| Intel | [GlobeTrek-Intel.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.dmg) | [GlobeTrek-Intel.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.zip) |

Disk image: open it and drag **Globe Trek** to **Applications**. Zip: open it, then drag the **Globe Trek** app it unpacks into **Applications**.

The app is not notarized by Apple, so the first time you open it macOS says it cannot verify it. Click **Done**, then go to **System Settings**, **Privacy & Security**, scroll down and click **Open Anyway** next to Globe Trek. The globe opens in Google Chrome or Microsoft Edge if one is installed, otherwise in your default browser. Quit Globe Trek from the Dock to stop it. Press **Option+M** for settings. Settings are kept in `~/Library/Application Support/Globe Trek`.

SHA-256: Apple Silicon dmg `1ae1c4636128406762ade3ea2ee50414bb96b1cfdd45b838837ca9558600f43a`, zip `10788ce0c6be72f5ebf1a3a9df3eebfd6dca78606dd246282a20490a90b4c3d7`  
SHA-256: Intel dmg `e100acf67659b4aa305388617f6cf3c814b50476bebfc27710bff6919370bc31`, zip `cae98047d6254f803b131e30293eac104e6986baab8175b56a2e2ed659e9e326`

## Android (Angela's phone)

**[Download Globe Trek Remote for Android](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrekRemote.apk)** (version 1.1.0)

If an older Globe Trek Remote is installed, uninstall it first: this version is signed differently and will not install over it.

Open the downloaded file on the phone and allow installing from your browser when Android asks. Then, on the PC, press Ctrl+M (Option+M on a Mac), open **Mode**, and either tap **Scan QR code** in the app, or scan the QR code with the phone camera and the app opens by itself.

SHA-256: `3b5418a72a68702d0b3cb74bdf76178d1a791fec141534583d4ba9a939d5fc1f`
