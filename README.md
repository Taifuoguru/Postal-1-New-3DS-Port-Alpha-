# Postal 1 New 3DS Port (Alpha)

This is a homebrew source port of the original **Postal 1 (1997)** engine, built specifically and exclusively for the **New Nintendo 3DS / New 2DS** family. 

> [!WARNING]
> **This is ONLY an engine port.** It does not contain any copyright-protected game assets or files. You **MUST** provide your own copy of the original PC game files to play this port. 

> [!IMPORTANT]
> This project is currently in an **early Alpha stage / Playable Demo**. Only one of the first demo levels is fully playable right now. It is far from complete, expect bugs, performance quirks, and rough edges. However, **development is active and will continue in the future!**

---

## 🚀 Features & Hardware Requirements

* **Exclusive to New 3DS / New 2DS:** Utilizes the higher CPU clock speeds, extra RAM, and the dedicated **C-Stick** of the "New" models. It will **not** run on Old 3DS.
* **Dual Movement Options:** Smooth navigation using either the Circle Pad or the D-Pad.
* **Twin-Stick Controls:** Full C-Stick aiming support for modern directional shooting control.
* **Playable Demo:** One level is fully up and running to test the core mechanics and control responsiveness on real hardware.

---

## 🕹️ Controls

| Input | Action |
| :--- | :--- |
| **Circle Pad / D-Pad** | Movement |
| **C-Stick** | Aiming / Reticle Direction |
| **A / X** | Fire / Shoot |
| **B / Y** | Interactions / Weapon Swap (Work in Progress) |

---



https://github.com/user-attachments/assets/d4484b0e-710e-46a6-92d0-880f92839c67

<img width="4000" height="3000" alt="20260704_203815" src="https://github.com/user-attachments/assets/7925b255-cb2e-45cf-865b-831a19833777" />





## 📦 Installation & Setup

To keep this project entirely legal and safe from DMCA takedowns, you must fetch the assets from your legally owned PC copy of Postal 1.

### 1. Install the Executable
Download the latest alpha page and install it on your console.

### 2. Prepare Game Assets & File Structure
You need to copy the original game directories and files into the specified folder on your SD card. 

* **Important Step:** You will also need to copy your original `postal.ini` file from your PC installation, rename it as required by the engine, and place it alongside the assets.

Create the following file structure on your 3DS SD card:


## 📦 Installation & Setup

To keep this project entirely legal and safe from DMCA takedowns, you must fetch the assets from your legally owned PC copy of Postal 1.

### 1. Install the Executable
Download the latest alpha `.3dsx` (and `.smdh`) from the Releases page and place them into your 3DS homebrew directory.

### 2. Prepare Game Assets & File Structure
You need to copy the original game folders and files into your port directory. 

* **Crucial Step for Config Files:** You must copy your original `POSTAL.INI` file from your PC installation, create a duplicate of it in the same folder, and rename that duplicate to `postal_plus.ini`. **Both files must exist in the same directory as shown below.**

Ensure your folder structure on the 3DS SD card matches this exactly:


<img width="827" height="600" alt="Ekran görüntüsü 2026-07-04 205912" src="https://github.com/user-attachments/assets/d0836455-9023-4a46-aff6-16a833b8a453" />

```text
sdmc:/3ds/postal1/  (Or your designated homebrew folder)
├── PostalPlus/        <-- (Original game folder)
├── res/               <-- (Original game folder)
├── title/             <-- (Original game folder)
├── POSTAL.INI         <-- (Original config file)
├── postal_plus.ini    <-- (Duplicate of POSTAL.INI, renamed)
├── postal1-3ds.3dsx   <-- (The homebrew executable)
└── postal1-3ds.smdh   <-- (The homebrew icon/metadata file)

