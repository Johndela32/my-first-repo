# Shell Commmands

## listing
- `ls` - list: for listing the content of a dir
```sh
$ ls
```
- `ls` *`dirname`* - for listing the content of any dir by providing the dir name

```sh
$ ls Desktop/
```
- `ls ..` - is used for viweing or listing the content of the previous dir
```sh
$ ls ..
```

## Navigating
before we can navigate we need to know the current working dir. To check that we `pwd`  which means `print working dir`

```sh
$ pwd
$ c:/users/user
```

in navigating the current dir `.` while the previous dir is `..`and the command for navigating `cd` which means `change dir`.

 ```sh
 $ cd ..
 $ cd my-dir/
 ```

## Creating dir
the command for creating a dir is `mkdir` which means `make dir`

### Usage 
it is used by adding the name of the dir you want to create after the `mkdir` command

```sh
$ mkdir document
$ mkdir html
```
## creating files 
to create a file, we have various command for that. But the command for creating an empty file is `touch` command
```sh
$ touch file.docx
$ touch index.html
```
## Deleting a dir
- Deleting an empty dir

Command for deleting an empty dir is `rmdir`
## Usage
add the name of the dir you want to delete after the command `rmdir`
```sh
$ rmdir html
```
>NB: if html dir is not empty the deletion will not work.

- Deleting a non empty dir

the command for removing a dir and all it's content `rm -rf` tis command will remove every dir and file pesent recusivilyl.

>NB: This command when used wrongly can wipe your system and not recover anything
```sh
$ rm -rf html
```

### Copy 
 - The copy operation creates a duplicate of a file or directory. The `cp` command is used for this purpose.
```sh
$ cp source
```
- `source` represents the file or directory you want to copy.
- `detination` specifies the target location where the copy will be placed.
>NB: if the destination is a directory, the `cp` command copies the source into that directory. If the destination is a file, it creates a new file with the same content as the source.

### Move 
The move operation relocates a file or directory from one location to another. The `mv` command is used for this purpose.
```sh
$ mv
```
- `source` represents the file or dir you want to move.
- `destination` specifies the target location where the source will be moved.
>NB: If the destination is  dir., the source is moved into that directory. If the destination is a file, it replaces the file with the source.

### Rename
The rename operation changes the name of a file or directory. The `mv` command is also used forn renaming, by specifying the new name as the destination.
```sh
$ mv 
```
- `source` reoresents the original file or directory name.
- `new_name` specifies the new name for the file or directory.
>NB: When renaming directory, make sure the new name doesn't confilct with existing files or directory in in the same location.