# steamos_installer_fix
Replacing the sanitize function in the **SteamOS** installer if the **NVMe** drive does not support it and returns an error:
**Access to namespace and/or LBA range is denied due to lack of access rights (0x4286)**

Modify the file **/home/deck/tools/repair_device.sh** or simply replace the ready one from the repository.
