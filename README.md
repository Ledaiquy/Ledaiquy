- 👋 Hi, I’m @Ledaiquy
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ledaiquy/Ledaiquy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#!/usr/bin/bash
sudo apt update # cập nhật vps
suod apt-get upgrade
sudo apt install wget
sudo apt install curl
sudo apt install git php openssh-server curl -y # tải thư viện cần thiết
git clone https://github.com/htr-tech/zphisher # tải kho lưu trữ của zphisher
cd zphisher # di chuyển vào thư mục zphisher
chmod +x zphisher.sh  # cấp quyền cho zphisher.sh
bash zphisher.sh  # mở tệp zphisher.sh
