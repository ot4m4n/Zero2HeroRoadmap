# Filesystems & Storage

> **Goal:** Understand how data is laid out on disk: partitions, filesystems, journaling, RAID.
> **Prerequisites:** 01, 03.
> **Estimated time:** 5–8 h

## 📚 Free resources

- [OSTEP — File System chapters](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [13Cubed — NTFS deep dives (YT)](https://www.youtube.com/@13Cubed)
- [Linux Filesystem Hierarchy (TLDP)](https://tldp.org/LDP/Linux-Filesystem-Hierarchy/html/)

## ✅ Checkpoint — you're ready to move on when:

- You can describe what happens on disk when you create, write to, then delete a file.

---

## 📂 Syllabus

## 💾 Filesystem Concepts

### What is a filesystem?
- Purpose and role in OS
- Relation to physical storage

### Structure of a filesystem
- Blocks, clusters, sectors
- Inodes (Unix/Linux)
- MFT (Windows NTFS)

### File types and metadata
- Regular files, directories, symbolic links
- Permissions and timestamps
- Hidden/system attributes

## 🧷 Common Filesystems

### FAT32
- Legacy use cases
- Max file/partition size
- Lack of permissions

### NTFS
- Journaling
- ACL-based permissions
- Alternate data streams (ADS)
- Encryption (EFS)

### exFAT
- Use in USB and SD cards
- Compatibility

### ext2/ext3/ext4
- Differences in journaling
- Use of inodes
- Linux compatibility

### Btrfs, XFS, ZFS (overview)

## 🧩 Storage Technologies

### HDD vs SSD
- Mechanical vs flash memory
- Lifespan, wear leveling

### Hybrid drives (SSHD)

### NVMe & SATA interfaces

### Storage controllers (RAID overview)
- RAID levels: 0, 1, 5, 6, 10
- Software vs Hardware RAID

## 🗂️ Mounting & Partitioning

### Partition tables
- MBR vs GPT
- Primary vs extended partitions

### Mounting concepts
- Mount points
- Fstab (Linux)
- Disk Management (Windows)

### Formatting and initialization
- Quick format vs full format
- Filesystem check (`chkdsk`, `fsck`)

## 🧪 Practical Tools & Utilities

### Windows
- Disk Management GUI
- `diskpart`, `format`, `chkdsk`, `fsutil`
- BitLocker (intro only)

### Linux
- `lsblk`, `fdisk`, `parted`, `mkfs`, `mount`, `umount`
- `df`, `du`, `fsck`, `tune2fs`, `blkid`

## 🔐 Security & Forensics Aspects

### Deleted file recovery
- File carving basics

### Journaling and write logs
- Use in incident investigation

### Hidden data and steganography

### Access control implications
- Permissions on file-level
- Filesystem encryption
