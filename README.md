# sdcloud

Mirror a directory from internal storage to external SD-card. Same as Google Backup, but is backup to memory card instead of cloud server.

eg.
```
/storage/emulated/0/Pictures (Internal)

to 

/storage/AE91-1775/Pictures (SD card)
```

Notes
- EXIF data are lost when copying from int to ext. Find ways to retain EXIF. otherwise the files use the date when they are copied from, rather than the creation date.
- Should have option to sync only when charging.
- Sync periodically (WorkManager)
- dangerous permission (MANAGE_EXTERNAL_STORAGE)
- Write in jetpack compose :) 
