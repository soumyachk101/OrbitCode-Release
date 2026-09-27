# OrbitCode Releases & Official Downloads

Official release repository and downloads for **OrbitCode** — the blazing fast, native workspace for AI agents and coding tools.

- **Main Repository:** [soumyachk101/Orbit-Code](https://github.com/soumyachk101/Orbit-Code)
- **Latest Release:** [Releases](https://github.com/soumyachk101/OrbitCode-Release/releases)
- **Website:** [OrbitCode Official Site](https://soumyachk101.github.io/OrbitCode-Release/)

---

## Downloads (v1.1.0)

Download the latest version for your platform from the [Releases page](https://github.com/soumyachk101/OrbitCode-Release/releases/latest):

| Platform | Architecture | File |
| :--- | :--- | :--- |
| **macOS (Direct DMG)** | Apple Silicon (arm64) | [`Orbit.dmg`](https://github.com/soumyachk101/OrbitCode-Release/releases/latest/download/Orbit.dmg) |
| **macOS (Versioned)** | Apple Silicon (arm64) | [`orbit-1.1.0-macos-arm64.dmg`](https://github.com/soumyachk101/OrbitCode-Release/releases/latest/download/orbit-1.1.0-macos-arm64.dmg) |
| **macOS Update Bundle** | Apple Silicon (arm64) | [`orbit-1.1.0-macos-arm64-app.tar.gz`](https://github.com/soumyachk101/OrbitCode-Release/releases/latest/download/orbit-1.1.0-macos-arm64-app.tar.gz) |
| **Windows** | x64 Portable | [`orbit-1.1.0-windows-x86_64.zip`](https://github.com/soumyachk101/OrbitCode-Release/releases/latest/download/orbit-1.1.0-windows-x86_64.zip) |
| **Linux** | x86_64 | [`orbit-1.1.0-linux-x86_64.tar.gz`](https://github.com/soumyachk101/OrbitCode-Release/releases/latest/download/orbit-1.1.0-linux-x86_64.tar.gz) |
| **Linux** | ARM64 | [`orbit-1.1.0-linux-aarch64.tar.gz`](https://github.com/soumyachk101/OrbitCode-Release/releases/latest/download/orbit-1.1.0-linux-aarch64.tar.gz) |

---

## macOS Installation

1. Download **`Orbit.dmg`** from the Releases section.
2. Open the disk image and drag **Orbit.app** into **/Applications**.
3. Launch Orbit from Applications or Spotlight.

> **Note on macOS Gatekeeper:**
> Because this is a free, open-source build not signed with an Apple Developer Program subscription, macOS Gatekeeper may show a verification dialog on first launch.
> - Go to **System Settings > Privacy & Security**, scroll to **Security**, and click **Open Anyway**.
> - Or run:
>   ```bash
>   xattr -cr /Applications/Orbit.app
>   ```

---

## Auto-Update

OrbitCode features built-in self-updating. When installed, Orbit automatically detects new versions published to this repository and prompts to apply updates seamlessly.

- **macOS:** Self-updating via the in-app update prompt or direct bundle swap.
- **Windows:** Auto-staging and portable executable swap.
- **Linux:** CLI / managed updating via `orbit update`.

---

## License

OrbitCode is open source and licensed under the [MIT License](LICENSE).
