# play_with_me

This repository was created as a safe play space for team mates wanting to try out git commands.

To use this repository, on your local machine:
```
git clone https://github.com/jonathanshapiro/play_with_me.git
```


add a file:
```
echo "hello" >> newFile.txt
git add newFile.txt
git commit -m"add new text file" 
git push origin master
```

modify an existing file:
```
git pull
... edit some file(s), say newFile.txt here 
git commit -m"modified text file to xxxx" newFile.txt
git push origin master
```
