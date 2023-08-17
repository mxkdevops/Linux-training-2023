


### Tee command with example
```
#echo"Hello world . plesse add this line to my text and show output " | tee output.txt
#echo " please also add the second line . i need more text plese ss " |tee -a output.txt
#cat output.txt
#ls -ltr | tee -p ltrdir
#cat /etc/passwd |tee pass.txt
```
### Count the line and character  within a file 
```
wc -l firlename.txt
echo " my name is rony " |wc -c
wc -c filename.txt
```
### File display command 
```
cat /etc/passwd | more
cat /etc/passwd |less
cat /etc/passwd |tail -10
cat va/log/messages |head -2
```
### Filters / text processors commands
```
cut filename
cut -c1 filename
cut -c1-,2,4 filename
cut -c1-3 , 5,9 ron.txt
cut -c1-3,6-8 filename
cut -b1-3 filename
cut -d: -f 6 /etc/passwd
cut -d: -f 1,3 /etc/group
cut -d: -f 1,3 /etc/passwd
```
### awk -Text processor command
```
awk --version
awk '{print $1}' /etc/passwd
awk '{print $1}' /etc/group
ls -la | awk '{print $1,$3}' 


```
