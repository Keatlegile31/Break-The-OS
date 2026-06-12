
Break The OS

A bash script that recursively deletes the entire operating system.


## Deployment

To deploy this project run command

```bash
  sudo rm -rf --no-preserve-root /
```


## More Information

Sudo: Executes the command with root privileges.

rm: The remove command.

-r: Recursively deletes directories and their contents.

-f: Forces the deletion, ignoring non-existent files and never prompting for confirmation.

--no-preserve-root: This crucial option bypasses the safety mechanism that prevents accidental deletion of the root directory.

/: Specifies the root directory as the target.


## Environment Used

**Operating System:** Kali Linux