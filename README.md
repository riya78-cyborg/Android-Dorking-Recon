# Android-Dorking-Recon
# Android Bug Bounty Hunting using Dorks & Recon Techniques

Welcome to the ultimate guide for finding **Android bug bounty targets** using simple yet powerful **Google Dorks**, **GitHub search filters**, and platform-specific techniques. This project is aimed at helping the community discover Android applications that are eligible for bug bounty — quickly and legally.

---

## What You’ll Learn
- How to find Android APKs using Google Dorks
- How to identify open-source Android apps for analysis
- How to find companies running Android apps on HackerOne, Bugcrowd, etc.
- Simple recon methods to build a hunting list
- Real-world examples and walkthroughs

---

## Folder Overview
- `dorks/`: Useful dorks for Google, GitHub, and platforms
- `tools/`: Recon tools and techniques
- `examples/`: Sample target discovery walkthroughs

---

## Requirements
- A browser (Google, GitHub)
- Optional: recon tools (like AssetFinder, Amass, etc.)
- Curiosity and patience

---

## Getting Started

### Step 1: Use Dorks to Discover APKs or Targets
- Check out [dorks/google-play-dorks.txt](./dorks/google-play-dorks.txt)
- Example:
site:play.google.com/store/apps/details?id=
site:github.com inurl:"AndroidManifest.xml"

### Step 2: Identify Bug Bounty Scope
- Cross-check the target in:
- https://hackerone.com/directory
- https://bugcrowd.com/programs
- https://intigriti.com/programs

### Step 3: Test the APK or Open-Source Code
- Download APK from APKPure or APKCombo
- Analyze using MobSF, JADX, Frida, etc.

---

## Contribute
Found a new dork or recon trick? Feel free to open a PR or issue.

---

## Created By
**Riya Nair** – Android Bug Bounty Trainer  

---

⭐️ Star this repo if you find it useful!
