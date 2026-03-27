# raid-5-setup-lab
RAID 5 configuration using BIOS and RAID controller (CompTIA A+ Lab)

🖥️ Environment
System: Dell workstation (virtual lab)
RAID Controller: PERC H200
Disks: 3 SATA drives

Steps
1️⃣ Enable RAID Mode in BIOS
Enter BIOS (F2)
Navigate to:
System Configuration → SATA Operation
Set:
SATA Mode = RAID On

2️⃣ Create RAID 5 Array
Restart system
Enter RAID configuration (Ctrl + I)
Select:
Create New Virtual Disk
Choose:
RAID Level = RAID 5
Select 3 disks (Press Space to select)
Create
