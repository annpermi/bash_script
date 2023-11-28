# Backup bash script

### Backup all the files in your home directory and save them all in .tar archive

The 3 options that we are giving to the tar command here does the following

- `c` - means that the `tar` command will create a new archive for the files provided
- `v` - is the verbose option, which just makes the command give output into the terminal whilst its running to show you its progress
- `f` - sets `tar` to use the input that follows this option as the name of the new archive created
- The `2> /dev/null` in this command just takes the standard error of the command and passes it to null. This is basically taking any error that might appear and throwing it away, so that it does not echo out to the user.
