<!-- 1. is javascript single threaded or multi-threaded ?
<details>
<summary>click to expand!</summary>
Javascript is a single-threaded language. This means it has one call stack and one memory heap. As expected, it executes code in order and must finish executing a piece code before moving onto the next. This is what allows Javascript to be  non-blocking and use async operations.<br>
However, Javascript also has asynchronous behavior. This is what allows us to use setTimeout,AJAX, and promises. These fuctions are handled by the browser, not by Javascript itself. This is what allows Javascript to be non-blocking for main thread operations 
</details> -->

# Linux Commands List

<details>
<summary>
 how to check your currnet location?
</summary>
#pwd :- present working directory/ print working directory

```
pwd
```
</details>

<details>
<summary>
 How to display name of current logged-in user?
</summary>

```
whoami 
```

</details>

<details>
<summary>
 How to check system date or time
</summary>
#date : if you want new new format date +%D for only date for hourse +%H

```
date
```
</details>

<details>
<summary>
 how to display files and directory present in current locations?
</summary>
#ls : how many file are there

```
ls
```

#ls -lt : in details info in files 

```
ls -lt
```

#ls -ltr : list file in reverse format

```
ls -ltr
```
#ls -lh : list file in human readiable format
```
ls -lh
```
</details>

<details>
<summary>
how to clear ternminal
</summary>
# also use clr+l
```
clear
```
</details>

<details>
<summary>
how to display content of file on terminal
</summary>

```
cat filename
```
</details>

<details>
<summary>
less command for searching
</summary>

```
less filename
```
take /key-name that whant you search go next world using N exp /hellow then press n
for forward order
for reverse order is use ?key-name

when you want to exit to editor press Q
</details>


<details>
<summary>
How to create new file in Linux?
</summary>

```
touch filename
```
</details>
<details>
<summary>
How to delete file in Linux?
</summary>

```
rm filename
```
</details>

<details>
<summary>
How to edit file in Linux?
</summary>

```
vi <file_name>
nano <file_name>
```

vi<file editor>
when we use vim editor "vi filename " to create new file or editiong exting files

start writing using press "i"
complet write all code press "ESC"
save and exit file using "shift+:"
then type "wq" 
</details>


<details>
<summary>
How to create directory/folder in linux?
</summary>

```
mkdir newFolder1
```
</details>
<details>
<summary>
How to delete directory/folder in linux?
</summary>

```
rmdir <dir_name>

rm -rf <dir_name>
```
</details>


<details>
<summary>
How to change path or move to another folder in Linux?
</summary>

```
rmdir <dir_name>

rm -rf <dir_name>
```
</details>

<details>
<summary>
How to change path or move to another folder in Linux?
</summary>

```
cd /path/folder
cd.. # one folder pise
cd../.. # two folder pise
```
cd / : this is root directory "/" of linux : jo sabase top pe hai aur jisake andhar sub folder or file hai ov root directory hai  


absoulte path: ekadam starting se path dena isako absolute path kahate hai
"exact paths"

relative path: hum jis location pe hai usake ralation me ya phir usake relative me jo path diya use relative path kahate hai
exp: me agar Desktop folder me hu Desktop  se cd/anand/Devops/"linux full course" jana ya hai relative path agar muje absoulte path dena hota to me 
cd /home/Desktop/anand/DevOps/"linux full course" karana padata for abosuole path
</details>


<details>
<summary>
how to copy paste to file this location to another location
</summary>

```
cp <file> /dest/path
```
</details>