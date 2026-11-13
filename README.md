# NoMid F-Droid Repository (`nomid.ws`)

Official self-hosted F-Droid repository for privacy-first, 100% offline, reproducible open-source Android releases by **NoMid**.

## Setup Instructions

1. **Install Official F-Droid (or a compatible client):**
   - [**Official F-Droid Download Page (`https://f-droid.org/`)**](https://f-droid.org/) (Direct APK: [`F-Droid.apk`](https://f-droid.org/F-Droid.apk))
   - Also works with [**Droid-ify**](https://github.com/Droid-ify/client/releases/latest) or [**Neo Store**](https://github.com/NeoApplications/Neo-Store/releases/latest).
2. **Add the NoMid Repository in F-Droid:**
   - Open **F-Droid &rarr; Settings &rarr; Repositories &rarr; + &rarr; Scan QR** and scan this QR code:

     <p align="center">
       <a href="#setup-instructions">
         <img src="qr-fdroid.svg" width="200" alt="Scan inside F-Droid (Settings -> Repositories -> + -> Scan QR) to add NoMid Repository" />
       </a>
     </p>

   - **Or** copy & paste this pinned Repository URL into **Settings &rarr; Repositories &rarr; +**:
     ```text
     https://raw.githubusercontent.com/nomid-ws/fdroid/main/repo?fingerprint=5B8E20619C48FD8F04A0174B4AE00D2C6AE24834B85EA77F57C5456AC9802532
     ```
3. **Install & Auto-Update:**
   - Refresh repositories in F-Droid, search **Prft Light Ctrl**, and tap **Install**.

- **Repository Index Signing Fingerprint (`SHA-256`):** `5B8E 2061 9C48 FD8F 04A0 174B 4AE0 0D2C 6AE2 4834 B85E A77F 57C5 456A C980 2532`
- **Obtainium Alternative (No F-Droid Required):** [**Add Prft Light Ctrl to Obtainium**](https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/nomid-ws/Prft_Lght_Ctrl)

## Included Packages

| App | Package ID | Latest Version | Summary | Source & Releases |
| :--- | :--- | :--- | :--- | :--- |
| **Prft Light Ctrl** | `app.prft.lightctrl` | `v1.5.1` (`7`) | Offline, account-free BLE studio lighting controller for Profoto AirX & AirTTL lights (`0` `INTERNET` permission, `neverForLocation` BLE) | https://github.com/nomid-ws/Prft_Lght_Ctrl |
