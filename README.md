# Linux Live USB Demo (Fedora Example)

This repository documents how to create a **Linux live bootable USB** using [balenaEtcher](https://etcher.balena.io/).  
The goal is to create a bootable USB that **does not overwrite your current operating system** — useful for demos, testing, and experimentation.

While this guide uses **Fedora Workstation** as the example, the same steps work for **most Linux distributions** that provide a live ISO (such as Ubuntu, Linux Mint, Zorin OS, or Manjaro).

<img width="920" height="460" alt="image" src="https://github.com/user-attachments/assets/b23055fc-01fe-4aa5-8fd3-b951b14554d8" />

---

## Requirements
- A USB drive (any size >= 8GB will work, but I am using 128GB)
- [balenaEtcher](https://etcher.balena.io/) (available for Linux, macOS, and Windows)
- A Linux ISO image (example: [Fedora Workstation](https://getfedora.org/))

---

## Steps

1. **Download a Linux ISO**
   - Example: [Fedora Workstation Live ISO](https://getfedora.org/)
   - Other options: [Ubuntu](https://ubuntu.com/download/desktop), [Linux Mint](https://linuxmint.com/), [Manjaro](https://manjaro.org/)
   - The ISO should be located in your downloads folder.
     
     <img width="1798" height="709" alt="image" src="https://github.com/user-attachments/assets/0da02fb4-ab4d-4ff9-b04c-e3bd0a814e48" />

2. **Insert the USB Drive**
   - Plug in your USB.
   - Back up anything important — the USB will be erased.

3. **Flash with balenaEtcher**
   - Open balenaEtcher.
   - Select the Linux ISO you downloaded.
  
     <img width="782" height="500" alt="image" src="https://github.com/user-attachments/assets/6d83c018-2ac2-478f-b347-c7cd156da452" />
     <img width="998" height="448" alt="image" src="https://github.com/user-attachments/assets/1ed21cd7-8a96-4e94-9e74-f7745cec5244" />
     <img width="1000" height="482" alt="image" src="https://github.com/user-attachments/assets/ebf5aa5d-755a-4e56-8377-943c1757c7b8" />

   - Only select your USB drive if it doesn’t pop up automatically.
   - Click **Flash!**

     <img width="995" height="491" alt="image" src="https://github.com/user-attachments/assets/8238bf25-65f5-4f35-b726-b5d2c65a6940" />
     <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1f925608-6a4d-4d53-90d2-01773c6cd20a" />

4. **Boot from the USB**
   - Restart your computer.
   - Enter the **boot menu** (`F12`, `F10`, `ESC`, or `Del`, depending on your machine).
   - Choose your USB drive.
  
     <img width="1348" height="1160" alt="image" src="https://github.com/user-attachments/assets/1d1e1596-fa3d-45d9-82fc-881c64d2b244" />
     <img width="1570" height="1134" alt="image" src="https://github.com/user-attachments/assets/a79462a3-0378-4744-a7c4-e099d3771e49" />

5. **Run Linux in Live Mode**
   - Most distributions will show a menu option such as:  
     **“Try [Distro] without installing”** or **“Start [Distro]-Live”**
   - Select that option.  
   - The system will run entirely from the USB, leaving your existing OS untouched.
  
   ## Before and After

This demo shows the transition from my existing OS (**Pop!_OS**) to running **Fedora Workstation** in live mode.  
The important detail: Pop!_OS remains untouched — Fedora is only running from the USB.

### Before (Pop!_OS as main OS)
<img width="1920" height="1080" alt="popos-desktop" src="https://github.com/user-attachments/assets/your-popos-screenshot-id" />

### After (Fedora Workstation Live USB)
<img width="1920" height="1080" alt="fedora-desktop" src="https://github.com/user-attachments/assets/your-fedora-screenshot-id" />


   <img width="1554" height="878" alt="image" src="https://github.com/user-attachments/assets/7d0dd086-b2c9-4108-894c-66f2060d57ce" />

