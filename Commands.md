<!-- 
<details>
<summary></summary>
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

cp ../<file> . : ek folder pise jake file name type karake space deke "." type kiya to oh file curent folder me copy ho gati hai 
cp ../<filename> . : "." current folder ko present karata hai 
```
</details>

<details>
<summary>How to copy content of a file to another file in linux</summary>

```
cp fileA file B
```
</details> 

<details>
<summary>how to cut-paste file one folder to another folder</summary>

```
mv <file> /dest/path/
```
</details> 


<details>
<summary>How to rename file</summary>

```
mv <filename> <newfilename>
```
</details> 

<details>
<summary>How to read or display top 5 lines from a file in Linux?</summary>

```
 head -5 file
 ```
</details>

<details>
<summary>How to read or display bottom 5 lines from a file in Linux?</summary>

```
 tail -5 file
 ```
</details>

<details>
<summary>How to sort the content from file in Linux?</summary>

```
sort file
sort -r file # for reverse
 ```
</details>

<details>
<summary>How to Display UNIQUE content from a file in Linux?</summary>

```
sort file | uniq
 ```
 "|" - pipe sign use first command execute first and out of fist command we perform next operation on this output use | pipe command lick binding 
</details>

<details>
<summary>A file has 9 lines. How to split this file in 3 different files in Linux?</summary>

```
split -l 3 file  # split -l : line of code 4 line filename
 ```
</details>

<details>
<summary>How to search a word and display matching content from a file in Linux?</summary>

```
#grep "word" file
 ```
</details>

<details>
<summary>How to search multiple word and display matching content from a file in Linux?</summary>

```
#egrep "word1|word2" file
 ```
</details>

<details>
<summary>How to use WILDCARDS  in Linux?</summary>
* [] {}

```
<file starting name>*:- file starting name particular name and end with anythings

*.<file extention>:- searching file using file extention

#when you want create new file in range use

touch file{1..10} # this command create 10 file in one command

 ```
</details>

<details>
<summary>How to  SHUFFLE  content of file in Linux?</summary>

```
shuf <filename>

```
</details>

<details>
<summary>How to  check if two files are identical or not in Linux</summary>

```
cmp <file1><file2>

```
return fileA fileB differ: byte 15, line 2

</details>

<details>
<summary>How to compare and display difference between two files in Linux</summary>

```
diff -u fileA fileB

```
return fileA fileB differ: byte 15, line 2

</details>

<details>
<summary>How to find a file in Linux</summary>

```
#find
find /path/-name <file>
# find command me find folder ke andhar andhar jake file search karata hai 

#updatedb
#locate <file>

#locate command me usaka apan ek database hai ho usame check karata hai bus apako updatedb command chalani padati hai locate comand use karane se pahale

```
</details>

## utility commands

<details>
<summary>How to display previously used commads in past </summary>

```
history
history | grep  <relative command>
```

</details>
<details>
<summary> How to check syntax and options availbale for a commands ?</summary>

```
<command> --help
<command> --help more #for line bye line read
```

</details>

<details>
<summary> How to read or get more info about a command ?</summary>

``` 
man <command>

```

</details>

<details>
<summary> How to check which executable is using for a command?</summary>

``` 
which <command>

```

</details>

<details>
<summary> How to use calculator in linux?</summary>

``` 
bc

```

</details>
<details>
<summary> how to check calender in last year of linux?</summary>

``` 
cal # display present month 
cal <year> display accourding give year

```

</details>


<details>
<summary> how to check How Long server has been running in Linux?</summary>

``` 

uptime
```

</details>

<details>
<summary> how to record your activity on terminal in a file?</summary>

``` 
script # starting recording command when it done press "cltr+d" it command create file that name typescript when you can type "cat typescript" run all command you recorded 
```

</details>


<details>
<summary> how to create a short-cut of a long command in LInux?</summary>

``` 
alias <commands >
```

</details>

## Zip and Unzip of Files and Folders

<details>
<summary> how to compress a file in Linux</summary>

``` 
gzip -k <file> # compress file and create zip file original file keep it
```

</details>

<details>
<summary> how to decompress a file in Linux</summary>

``` 
gzip -d <file> # decompress file and remove zip file 
gunzip <file>
```

</details>


<details>
<summary> how to compress a folder in Linux</summary>

``` 
tar -czf myfile.tar.zip myfiles
czf  # compreess zip format folder
```

</details>

<details>
<summary> how to decompress a folder in Linux</summary>

``` 
tar -xzf myfile.tar.zip 
xzf  # extract zip  folder
```

</details>

<details>
<summary> how to compress multiple files in one zipped file in Linux</summary>

``` 
zip myfiles.zip file1 file2

# for unzip file
unzip <myfile.zip>
```

</details>

<details>
<summary> how to list files in zipped file?</summary>

``` 
# when you want kwon how many file in ziped file and there name use this command

unzip -l myfiles.zip
```

</details>

## Downloading Files from Internet

<details>
<summary> how to download a file from internet?</summary>

``` 
wget URL_of_file 

wget -O opt_file.txt URL_Of_files # when you want to change file name in this case file.txt
```

</details>

<details>
<summary> how to call an API on Linux?</summary>

``` 
#you can get request using this command

curl http://numbersapi.com/random
```

</details>


<details>
<summary> how to install an application on Linux?</summary>

``` 
apt or yum/dnf
```

</details>

<details>
<summary> how to check if an application is installed or not on linux?</summary>

``` 
rpm -qa | grep application name
dnf list installed
```

</details>

<details>
<summary> how to list available packages to install on Linux?</summary>

``` 
apt search <package_name>
yum/dnf list available
```

</details>
<details>
<summary> how to start stop service  on Linux?</summary>

``` 
systemctl start/stop service_name
```

</details>


<details>
<summary> how to list all service on Linux?</summary>

``` 
systemctl list-units --type=service --all
```

</details>