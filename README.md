# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

* cp (folder and individual files)
---

__rm__ - _remove files or directories_

__Examples:__

``` 
rm filename.cpp
rm myFolder
```
---

__rmdir__ - _remove empty directories_

__Examples:__

```
rmdir myFolder
```
---

__ln -s__ - _ln: make links between files. -s: make symbolic links instead of hard links._

__Example:__

```
ln -s filenameMain.cpp fiilenameSupport.cpp
```
---

__scp__ - _secure copy_

__Example:__

```
scp filename.cpp myCopy.cpp
```
---

__pwd__ - _print name of current/working directory_

__Example:__

```
pwd (screen displays: USER/myFolder/subFolder)
```
---

__ls__ - _ls: list directory contents. ls -a: list all directory contents(including hidden files)._

__Examples:__

```
ls (screen displays: filename1.cpp filename2.txt filename3.cpp README.md filename5.txt)
ls *.txt (screen displays: filename2.txt filename5.txt)
ls -s (screen displays: filename1.cpp filename1.cpp~ filename2.txt filename3.cpp filename3.cpp~ README.md filename5.txt)
```
---

__tar__ - _creates an archive of given folders_

__Examples:__ 

```
tar cfvz archiveFolder.tgz folderBeingArchived folderBeingArchived2
```
---

## File Transfer

__curl__ - _transfer a URL_

__Example:__

```
curl http://webAddressGoesHere.com
curl -o http://webAddressGoesHere.com
```
---

__wget__ - _non-interactive netowrk downloader_

__Example:__

```
wget http://webAddressGoesHere.com
```
---

__rsync__ - _a fast, versatile, remote(and local) file-copying tool_

__Example:__

```
rsync filename.cpp copyFile.cpp
```
---

## Pipe tools

__cat__ - _prints out the contents of a file_

__Example:__

```
cat filename.cpp
less filename.cpp
```
---

__sort__ - _sorts lines of text files_

__Example:__

```
sort filename.cpp
less filename.cpp | sort
```
---

__uniq__ - _reports repeated lines_

__Example:__

```
uniq filename.cpp
less filename.cpp | uniq
less filename.cpp | uniq -c
```
---

__grep__ - _a way of searching for a character or word_

__Example:__ 

```
grep *.txt
grep "character" filename.cpp
```
---
