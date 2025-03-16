# OneDrive Backup to external
 Backs up OneDrive to a specified external drive in near real time

First, configure the JSON file as needed. Next, run Powershell script "OneDriveBackup.ps1", which creates a full backup of OneDrive to a specified external drive. Then run "Create-OneDriveBackupTask.ps1". This creates a Scheduled Task that continuously monitors the OneDrive folder and backs up (not syncs) new and changed files from OneDrive to the external drive. Enjoy!
