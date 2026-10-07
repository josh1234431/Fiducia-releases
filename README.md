# Fiducia releases

Installers for **Fiducia**, the aerial photogrammetry workstation I've been building. It takes scanned
film or digital aerial photographs through to orthophotos, mosaics and elevation models in one
workspace, and it tells you exactly how accurate every step is.

## Download

Get the latest installer from the [Releases page](https://github.com/josh1234431/Fiducia-releases/releases/latest).

- Windows 10 or 11, 64-bit
- Installs just for you, so no admin rights are needed
- The installer isn't signed yet, so Windows SmartScreen will ask first. Choose **More info**, then **Run anyway**

Each release lists the installer's SHA-256, so you can check the download with:

```powershell
Get-FileHash .\Fiducia-Setup-0.1.0.exe -Algorithm SHA256
```

## Feedback

Fiducia is very much still a prototype. Any feedback or questions are much appreciated, whether
something breaks, feels awkward, or you'd expect it to work differently. Open an issue here or get in
touch on [LinkedIn](https://www.linkedin.com/in/joshua-metcalf-1b2184263).
