
# Windows Server Backup and Recovery Lab

Status: In Progress

## 1. Lab Overview

Configure and test Windows Server Backup in a virtualized Active Directory environment, focusing on system state backups, recovery procedures, and backup verification.

## 2. Lab Environment
- Hypervisor: Oracle VM VirtualBox
- Operating System: Windows Server 2025
- Active Directory Domain Services (AD DS)
- DNS Server
- Windows Server Backup
- Dedicated virtual backup disk

## 3. Backup Storage Configuration
To simulate backup storage, I created an additional virtual hard disk in the VirtualBox VM and formatted it.

Steps
  1. Created an 80gb virtual disk on VirtualBox (Insert screenshot)
  2. Attached disk to to the server VM.
  3. Started Windows Server VM and booted Disk management, infantilized disk and formatted as E: Drive
<img width="373" height="133" alt="image" src="https://github.com/user-attachments/assets/cce2a152-ba22-447f-a5f3-9fb8dde19d0d" />

  4. Lastly, Verify the backup volume is accessible in file explorer.
<img width="273" height="121" alt="image" src="https://github.com/user-attachments/assets/4c354395-7019-41ad-82bd-e545c541be10" />

## 4. Installing Windows Server Backup
