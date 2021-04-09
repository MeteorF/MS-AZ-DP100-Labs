<!-- #region -->
1. Change Directory to "Users"
``` bash
cd ..
```
<!-- #endregion -->

2. Make an empty directory
```
mkdir copy-mslearn-dp100
```


3. Copy the lab materials recursively into the new folder (denoted as folder 1)
```
cp -R mslearn-dp100/* copy-mslearn-dp100/
```


4. Go to Github, create a new repository


5. Git clone the new Github repo into the machine (denoted as folder 2)
```
Git clone <your new repo address>
```


6. Copy the lab materials recursively from folder 1 to folder 2
```
cp -R copy-mslearn-dp100/* <your new repo name>
```


7. Go to folder 2
```
cd <your new repo name>
```


8. Git stage new files
```
Git add .
```


9. Git commit new files
```
Git commit -m "Test commit"
```


10. Upload to your new Github repo
```
Git push
```


(Repeat Step 8 - 10 to sync changes if you added/changed/deleted anything) <br>
You may use below syntax to check if any changes pending to sync
```
git status
```
