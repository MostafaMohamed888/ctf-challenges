# Forensics 

## Easy Challenges
| Challenge Name  | Description | Hint
|:-- | :-- | :---
| [file-desc](file-desc) | What type of file is this? | Did you add the output to jctf{INSERT_FILE_TYPE_HERE}? 
| [HASH-browns](HASH-browns) | Get the decimal sum of the last 4 digits of all each file from an hash. They were talking about something pertains to md as the hash. | Did you convert it from hex to decimal? And did you make sure to get only the last 4 digits? Also make sure it is between the jctf{} flag formatter.
| [investigating-windows](investigating-windows) | Find the SID of the user robbr using the Windows registry files provided. | Try reg ripper?
| [data-about-data](data-about-data) | Find the flag in this zip archive. | Cameras produce a lot of metadata.

## Medium Challenges
| Challenge Name  | Description | Hint
|:-- | :-- | :---
| [closed-creds](closed-creds) | Using the registry files provided, what is the password of the Administrator user? | Research dumping hashes from SAM.
| [where-did-you-go](where-did-you-go) | Find the flag in this forensic disk image. | Research the NTFS Recycling. 


## Hard Challenges
| Challenge Name  | Description 
|:-- | :-- 
| [alternate-reality](alternate-reality) | Find the flag in this forensic disk image.  
| [pw-backup](pw-backup) | I seem to not be getting the full and grand picture here