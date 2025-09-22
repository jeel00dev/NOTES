# 📱 Mounting Android Phone with jmtpfs (Void Linux)

Use `jmtpfs` to transfer files between your Android phone and Void Linux.

---

## 🔹 Quick Steps

# 1. Install

sudo xbps-install -S jmtpfs
mtp-detect to detect file sharing Devices
jmtpfs --device=N ~/phone where N is index of device in mtp-detect.

# 2. Plug phone & enable File Transfer (MTP) mode

# (not Charging, not USB Tethering)

# 3. Create mount point

mkdir -p ~/phone

# 4. Mount

jmtpfs ~/phone

# 5. Access files

ls ~/phone

# 6. Unmount when done

fusermount -u ~/phone
