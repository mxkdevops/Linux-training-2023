## Tee commands input the result and also display the output.
```
echo " my name is rony . my brother name is rigun " | tee ron.text
```

### Append text to the same file -a option
```
echo " hi please add my sister name in the list " |tee -a ron.text

ls -ltr |tee ltrdir.txt
cat ltrdir.text
```
## add with -p option if any error it will still execute
```
echo "Error test" | tee -p warn-error.txt

```
### Help with tee command 
```
tee --help
```
