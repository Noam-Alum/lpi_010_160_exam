# LPI 010-160 practice exam

The Linux Essentials certificate validates a demonstrated understanding of the following: FOSS, the various communities, and licenses. Knowledge of open source applications in the workplace as they relate to closed source equivalents.

<p align="center">
  <img src="https://www.lpi.org/wp-content/uploads/2023/04/Essentials-Linux_250_0.png" alt="alt text">
</p>

This code lets you practice for LPI 010-160 (Linux Essentials) with real questions from the exam.

<hr>

# Installation

## OS X & Linux:
### wget
```sh
# Install via wget
wget -O lpi_010_160_exam.zip https://codeload.github.com/Noam-Alum/lpi_010_160_exam/zip/refs/heads/main
unzip lpi_010_160_exam.zip
mv lpi_010_160_exam-main/lpi_linux.py .
rm -rf lpi_010_160_exam-main/ lpi_010_160_exam.zip
```
### git clone
```sh
# Install via git clone
git clone --single-branch --branch main --depth 1 https://github.com/Noam-Alum/lpi_010_160_exam.git && mv lpi_010_160_exam/lpi_linux.py . && rm -rf lpi_010_160_exam
```
<hr>

## Windows:
### wget
```sh
# Install via wget
wget -O lpi_010_160_exam.zip https://codeload.github.com/Noam-Alum/lpi_010_160_exam/zip/refs/heads/main
Expand-Archive -Path 'lpi_010_160_exam.zip' -DestinationPath '.'
Move-Item -Path 'lpi_010_160_exam-main\lpi.py' -Destination '.'
Remove-Item -Path 'lpi_010_160_exam-main' -Recurse -Force
Remove-Item -Path 'lpi_010_160_exam.zip' -Force

```
### git clone
```sh
# Install via git clone
git clone --single-branch --branch main --depth 1 https://github.com/Noam-Alum/lpi_010_160_exam.git
move lpi_010_160_exam\lpi.py .
rmdir /s /q lpi_010_160_exam

```

<br>
<hr>

# Usage example
## This section is reffering to linux users.
### set privileges
Firstly you need to fix the scripts permission
```sh
chmod +x lpi_linux.py
```

### Run the script
After fixing the permissions of the file we can run the script with the following commands:
```sh
./lpi_linux.py
# or
/usr/bin/python3 lpi_linux.py
```
> You must have python3 installed!

<br>

Then you should get the first question of the bunch, e.g. :
```sh
1| What are the differences between hard disk drives and solid state disks? (Choose two.)

Options:

1) Hard disks can fail due to physical damage, while solid state disks cannot fail.
2) Solid state disks can store many times as much data as hard disk drives.
3) /dev/sda is a hard disk device while /dev/ssda is a solid state disk.
4) Solid state disks provide faster access to stored data than hard disks.
5) Hard disks have a motor and moving parts, solid state disks do not.
>
```

<hr>
<p align="center">
  <img src="https://pakhotin.org/wp-content/uploads/2023/07/53113-106400-Linux-xl-1024x576.jpg" alt="alt text">
</p>

## Contact

Noam Alum – [Website](https://alum.sh) – nnoam.alum@gamil.com
