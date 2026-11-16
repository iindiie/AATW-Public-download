# Globe Trek - Discovering Angela

## Windows (the PC that runs the globe)

**[Download the Windows installer](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Setup.exe)** (version 1.5.1, about 28 MB)

Run the installer. No admin rights are needed. If Windows SmartScreen appears, choose **More info**, then **Run anyway**, because the installer is not code signed. When Windows asks whether Globe Trek may use the network, allow it on **Private networks** so the phone app can reach it.

SHA-256: `5dd6d59de79d78c38ebf8564f2e2e73412d251df84924e5ebe6837a2ec8c6989`

## Mac

Not sure which Mac you have? Apple menu, **About This Mac**: "Chip: Apple M..." means Apple Silicon.

| | Disk image | Zip (if the disk image will not open) |
|---|---|---|
| Apple Silicon (M1 to M4 and later) | [GlobeTrek-AppleSilicon.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.dmg) | [GlobeTrek-AppleSilicon.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.zip) |
| Intel | [GlobeTrek-Intel.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.dmg) | [GlobeTrek-Intel.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.zip) |

Disk image: open it and drag **Globe Trek** to **Applications**. Zip: open it, then drag the **Globe Trek** app it unpacks into **Applications**.

The app is not notarized by Apple, so the first time you open it macOS says it cannot verify it. Click **Done**, then go to **System Settings**, **Privacy & Security**, scroll down and click **Open Anyway** next to Globe Trek. The globe opens in Google Chrome or Microsoft Edge if one is installed, otherwise in your default browser. Quit Globe Trek from the Dock to stop it. Press **Option+M** for settings. Settings are kept in `~/Library/Application Support/Globe Trek`.

SHA-256: Apple Silicon dmg `b230e5077a7ea75000dd89a29e3078495baeea4b1e054e77fda34a981b673ad9`, zip `9e32ef5584d2fd48271021b953421af7583004e84bab7708a316d4d64530f723`  
SHA-256: Intel dmg `d6b9e9b8c1f43c0b0661ee89bc7326c72135db5054883319c0217f2c4cc74104`, zip `58be06cd2694da39970fa5c6bfb373cd139e511ee941d60638c64a8c45055e1e`

## Android (Angela's phone)

**[Download Globe Trek Remote for Android](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrekRemote.apk)** (version 1.3.0)

If an older Globe Trek Remote is installed, uninstall it first: this version is signed differently and will not install over it.

Open the downloaded file on the phone and allow installing from your browser when Android asks. Then, on the PC, press Ctrl+M (Option+M on a Mac), open **Mode**, and either tap **Scan QR code** in the app, or scan the QR code with the phone camera and the app opens by itself.

SHA-256: `5ea32e969e71e22397c570a157fc35fb1c8bea9977b480e4c6fbd1c4c2295654`
