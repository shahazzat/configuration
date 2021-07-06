# Make ZIP file
## Create encrypted zip
```
shahazzat@Mohammads-MacBook-Pro ~ % zip -er9 test.zip google_map.html
Enter password: 
Verify password: 
  adding: google_map.html (deflated 90%)
shahazzat@Mohammads-MacBook-Pro ~ % ls
Sushi Arai - Google Maps.html	Untitled.ipynb			google_map.html			tutorial-env
Sushi Arai - Google Maps_files	gmapdata.html			test.zip
```
## Unzip file
```
shahazzat@Mohammads-MacBook-Pro ~ % unzip test.zip
Archive:  test.zip
   creating: test/
[test.zip] test/.DS_Store password: <Type your pass>
```
## Update zip contents
```
zip -ur <dir_name> <zip_file_name>
shahazzat@Mohammads-MacBook-Pro ~ % zip -ur test test
```
