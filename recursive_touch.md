Touch is a command to update the date and time of a particular file(s) or directory (to the present date and time). This command will 'touch' all files and recursive files in the current and recursive directory (but not the directories themselves).

```find . -type f -name "*.txt" -exec touch {} +```

The ```.``` can be changed to a particular file name or directory name, and the ```f```, which stands for 'file' can be changed to ```d``` for directories.
