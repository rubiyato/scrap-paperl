# 🌀 real men tutorial 500 🌀

yossup gangers js copy n paste this to the termux ya jus downloaded one by one from top to bottom dont forget top to bottom men ✨🫱🏻‍🫲🏼btw you guys must have your own termux so my three files can come and rent the entire termux to live in.dont forget that you need avnc to actually use this n stuff

---

### 1. setup storage & install tools
*note it will ask for storage permission here don't worry that is just for the thing it's needed for here )* 

go ahead and tap allow
```bash
termux-setup-storage
```

now run this command
```bash
pkg install git git-lfs proot-distro -y
```

---

### 2. clone the repository
```bash
cd /sdcard/download
git clone https://github.com
cd scrap-paper
```

---

### 3. recombine the backup parts
```bash
cat linux_backup_part_* > linux_backup.tar
```

---

### 4. extract the linux environment
```bash
cd /data/data/com.termux/files/usr/var/lib/proot-distro/containers
tar -xvf /sdcard/download/scrap-paper/linux_backup.tar
```

---

### 5. launching your desktop
type this command in termux
```bash
proot-distro login ubuntu
```

inside that terminal, type this to start it up
```bash
vncserver
```

---

### 6. connect via avnc app
1. open the **avnc** app.
2. connect to `localhost 5901`
3. type your password and tell that save button to stop hitting itself(aka click it)

---

### note
heres the discord incase any errors happen, i kinda rushed this and im s lillll bit new to this pls spam ping not so evil ae in either the server or in dms like 5-20 times, when i wake up ill answer ur messages :D

https://discord.gg/2S4vgKZJr8 <==the server
