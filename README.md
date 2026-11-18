# Globe Trek - Discovering Angela

## Windows (the PC that runs the globe)

**[Download the Windows installer](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Setup.exe)** (version 1.5.3, about 28 MB)

Run the installer. No admin rights are needed. If Windows SmartScreen appears, choose **More info**, then **Run anyway**, because the installer is not code signed. When Windows asks whether Globe Trek may use the network, allow it on **Private networks** so the phone app can reach it.

SHA-256: `435b8345ad6c61fabeaab4cf9f1ee15f9b639235d6f45e0a5d2bbc12c8093ce3`

## Mac

Not sure which Mac you have? Apple menu, **About This Mac**: "Chip: Apple M..." means Apple Silicon.

| | Disk image | Zip (if the disk image will not open) |
|---|---|---|
| Apple Silicon (M1 to M4 and later) | [GlobeTrek-AppleSilicon.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.dmg) | [GlobeTrek-AppleSilicon.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.zip) |
| Intel | [GlobeTrek-Intel.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.dmg) | [GlobeTrek-Intel.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.zip) |

Disk image: open it and drag **Globe Trek** to **Applications**. Zip: open it, then drag the **Globe Trek** app it unpacks into **Applications**.

The app is not notarized by Apple, so the first time you open it macOS says it cannot verify it. Click **Done**, then go to **System Settings**, **Privacy & Security**, scroll down and click **Open Anyway** next to Globe Trek. The globe opens in Google Chrome or Microsoft Edge if one is installed, otherwise in your default browser. Quit Globe Trek from the Dock to stop it. Press **Option+M** for settings. Settings are kept in `~/Library/Application Support/Globe Trek`.

SHA-256: Apple Silicon dmg `933f9f9089973730075602b554a4201f3b46ac06d896abc51b744e5902806953`, zip `e4e8dc449ce6b862398a317630b1b513034c4eab3d572ea62eaa3676e02f1cb9`  
SHA-256: Intel dmg `f57bea6c8668175395ad0319edd10c052646a6160c92cecc4ab417ebf6849ba5`, zip `5ccd78fe0dc07ea9f8bf8b05603be5cf0d3fac3a6f87b53fcef0cbb9ff6c3a1d`

## Android (Angela's phone)

**[Download Globe Trek Remote for Android](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrekRemote.apk)** (version 1.3.0)

If an older Globe Trek Remote is installed, uninstall it first: this version is signed differently and will not install over it.

Open the downloaded file on the phone and allow installing from your browser when Android asks. Then, on the PC, press Ctrl+M (Option+M on a Mac), open **Mode**, and either tap **Scan QR code** in the app, or scan the QR code with the phone camera and the app opens by itself.

SHA-256: `5ea32e969e71e22397c570a157fc35fb1c8bea9977b480e4c6fbd1c4c2295654`
