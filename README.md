# Masarat for Windows

Public Windows installers for the Masarat school-transport operations manager.

## Download

Open the [latest release](https://github.com/burawi/masarat-releases/releases/latest) and download the file ending in `x64-setup.exe`.

Masarat connects to the production Masarat service. An administrator access key is required to use protected management functions.

## Windows warning

The installer is currently unsigned. Microsoft Defender SmartScreen may display **Windows protected your PC**. Select **More info**, confirm that the file came from this repository, and then select **Run anyway**.

For additional assurance, download the matching `.sha256` file and compare it with:

```powershell
Get-FileHash .\Masarat-Operations-0.1.2-x64-setup.exe -Algorithm SHA256
```

Source code is maintained separately in a private repository. This public repository contains release downloads and end-user instructions only.
