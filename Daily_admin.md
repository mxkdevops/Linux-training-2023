


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
### pipe command 
```
cat /etc/passwd | more
cat /etc/passwd |less
cat /etc/passwd |tail -10
```
