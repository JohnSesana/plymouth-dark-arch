# Dark Arch - My Custom Plymouth Boot Screen
*A personalized boot splash theme, inspired by and modified from [Omarchy - An opinionated Arch + Hyprland Setup by DHH](https://omarchy.org/).*

---

## 🖼 Preview

<!-- Insert screenshots or GIFs below -->
<img width="1674" height="958" alt="image" src="https://github.com/user-attachments/assets/a7e7b0ab-90fb-4023-a0ab-67a32e5bdd39" />



---

## ✨ Features

- Based on **Omarchy** with custom modifications
- Fully compatible with systems using **Plymouth** (e.g., Ubuntu, Debian, Arch)
- Lightweight and smooth experience during boot

---

## 📁 Files Included

- `dark-arch.plymouth` – Main theme descriptor
- `dark-arch.script` – The animation script file
- All custom images used in the animation are in the main folder
- `README.md` – This file

---

## 🛠 Installation

  > ⚠️ You need root access to install Plymouth themes.
  
  1. **Copy the theme folder:** 
  
  ```bash
  sudo cp -r dark-arch /usr/share/plymouth/themes/
  ```
  
  ```bash
  plymouth-set-default-theme
  ```
  
  - You should see: 
  `dark-arch`
  
  Then just reboot your system and enjoy your new lock screen!

---

## ⚠️ Disclaimer
- This Plymouth theme is provided as-is without any warranty or guarantee.
- I am not responsible for any damage, misconfiguration, or boot issues that may occur as a result of installing or using this theme.
- Install and use at your own risk. Make sure you understand how to recover your system in case something goes wrong.
- It is recommended to test on a non-critical machine or virtual environment first.
   
