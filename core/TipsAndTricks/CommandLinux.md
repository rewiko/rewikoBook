# Linux commands

Extract many zip:
````
ls *zip | xargs -i unzip {}
````

OR 
```
for file in *.zip
do
unzip $file
done
```