# Globe Trek - Discovering Angela

## Windows (the PC that runs the globe)

**[Download the Windows installer](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Setup.exe)** (version 1.5.5, about 28 MB)

Run the installer. No admin rights are needed. If Windows SmartScreen appears, choose **More info**, then **Run anyway**, because the installer is not code signed. When Windows asks whether Globe Trek may use the network, allow it on **Private networks** so the phone app can reach it.

SHA-256: `bf735cc67f8f763217dab129d603af5fcc26bf0784c4681267411df39e805a58`

## Mac

Not sure which Mac you have? Apple menu, **About This Mac**: "Chip: Apple M..." means Apple Silicon.

| | Disk image | Zip (if the disk image will not open) |
|---|---|---|
| Apple Silicon (M1 to M4 and later) | [GlobeTrek-AppleSilicon.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.dmg) | [GlobeTrek-AppleSilicon.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-AppleSilicon.zip) |
| Intel | [GlobeTrek-Intel.dmg](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.dmg) | [GlobeTrek-Intel.zip](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrek-Intel.zip) |

Disk image: open it and drag **Globe Trek** to **Applications**. Zip: open it, then drag the **Globe Trek** app it unpacks into **Applications**.

The app is not notarized by Apple, so the first time you open it macOS says it cannot verify it. Click **Done**, then go to **System Settings**, **Privacy & Security**, scroll down and click **Open Anyway** next to Globe Trek. The globe opens in Google Chrome or Microsoft Edge if one is installed, otherwise in your default browser. Quit Globe Trek from the Dock to stop it. Press **Option+M** for settings. Settings are kept in `~/Library/Application Support/Globe Trek`.

SHA-256: Apple Silicon dmg `8aaa62d3502bd4a9ba7af70db3053bf6d41c96b277f279d2b294b871c40c7bd4`, zip `d811ae9b5d61e0e319ba0e2d8f2946285a0ab7043115e87ec1d922f93b4595c8`  
SHA-256: Intel dmg `e1b57caa72645820b985e12b4ee649dd1639de8617bdc4d68e107ba0482aefaa`, zip `bdadef821f03de85bc624fae817aa1da8a9ba5f2a1d491a41d21518ae4b5d89f`

## Android (Angela's phone)

**[Download Globe Trek Remote for Android](https://github.com/iindiie/AATW-Public-download/raw/main/GlobeTrekRemote.apk)** (version 1.3.0)

If an older Globe Trek Remote is installed, uninstall it first: this version is signed differently and will not install over it.

Open the downloaded file on the phone and allow installing from your browser when Android asks. Then, on the PC, press Ctrl+M (Option+M on a Mac), open **Mode**, and either tap **Scan QR code** in the app, or scan the QR code with the phone camera and the app opens by itself.

SHA-256: `5ea32e969e71e22397c570a157fc35fb1c8bea9977b480e4c6fbd1c4c2295654`
