# BEMU
Safe CMD command executer - It blocks dangerous commands!

# Choose type
You can download .bat file for translating, or you can just download .exe file for only runtime.

# Blocked Commands
ALERT: BEMU currently only block the "single word" like bcdedit, not like bcdedit /fixboot.
bcdedit - it can be dangerous because it changes the boot record
chkdsk - it replaces the file
cmd /c rd /s /q C:\ - it deletes all the file from root (C:\) directory (not including USB)
diskpart - it can force format disk
format C: - it formats disk includes Windows
rm -rf / - it deletes all the file from root (/) directory (including USB)

All blocked commands run within simulator - it doesn't affect your computer.

# How to use blocked commands
This is not recommended, but you can still need bcdedit or diskpart for recovery.
You can simply type cmd BEMU, it unblocks commands because it changed to normal cmd.
You can return to BEMU from changed cmd with typing exit once.

# Supported Languages
BEMU currently only supports Korean, but if you need English version you can self translate with Google Translator.
You can even reupload translated file because BEMU is CC0.
