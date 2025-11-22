🛠️ Installation

📌 Kali Linux

sudo apt update
git clone https://github.com/mrwhite4939/steghide.git
cd steghide
bash steghide.sh
---
📌 Termux (Android)

Steghide is not officially available on Termux packages,
but you can install it manually using pkg + build tools:

pkg update && pkg upgrade
pkg install steghide

⚠ If steghide is not found, install from a compiled package:

pkg install git clang make automake
git clone https://github.com/Steghide/steghide.git
cd steghide
bash steghide.sh
