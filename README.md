# Mass-delete-windows-profiles
This deletes all the profiles on a computer instead of going through SystemPropertiesAdvance. This deletes the registry entry. If that deletion is successful, then proceed to delete the profile folder. This way, if the registry deletion fails, the script will skip the profile deletion.

USE POWERSHELL IN ADMIN MODE!
Also change "yourusername" to your username
