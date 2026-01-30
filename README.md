# Linux Storage Administration

This project demonstrates foundational Linux storage administration by configuring additional disks, partitions, filesystems, persistent mounts, and swap space on a Linux system.

It simulates common real-world tasks performed by Linux system administrators when managing server storage.

---

## Project Scope

- Disk attachment and detection  
- Disk partitioning  
- Filesystem creation  
- Mounting and persistent configuration  
- Swap space setup and activation  

---

## Technologies & Tools

- RHEL 9 (Linux)  
- lsblk  
- fdisk / parted  
- mkfs (ext4/xfs)  
- mount and /etc/fstab  
- mkswap and swapon  

---

## Implementation Overview

1. Attached an additional disk and verified it within the system  
2. Created disk partitions for storage and swap  
3. Formatted partitions with Linux filesystems  
4. Mounted storage partitions and configured persistence using `/etc/fstab`  
5. Created and enabled swap space  

---

## Skills Demonstrated

- Linux disk and partition management  
- Filesystem administration  
- Persistent mount configuration  
- Swap memory management  
- Basic troubleshooting  

---

## Environment

- AWS EC2 instance running RHEL 9  

---

## Result

Successfully configured additional storage with persistent mounts and active swap, reflecting real-world Linux storage administration workflows.












