    1  mkdir first_repo
    2  ls
    3  cd Pulpit
    4  mkdir first_repo
    5  git
    6  sudo apt install git
    7  cd first_repo/
    8  touch test.txt
    9  nano test.txt
   10  git init
   11  git status
   12  git add test.txt
   13  git commit
   14  git config --global user.email "sylwek.wielun@gmail.com"
   15  git config --global user.name "sylwek84"
   16  git log
   17  git commit
   18  nano test.txt
   19  git status
   20  git add .
   21  git commit -m"zmienilem"
   22  git log
   23  nano test.txt 
   24  git status
   25  git commit -m"kolejna proba"
   26  git status
   27  git commit -m"kolejnazmiana"
   28  git commit -m "kolejnazmiana"
   29  git add .
   30  git status
   31  git commit -m "kolejnazmiana"
   32  git log
   33  git commit
   34  git remote add origin http://github.com/sylwek84/first_repo.git
   35  git push -u origin master
   36  git remote add origin https://github.com/sylwek84/first_repo.git
   37  git push -u origin master
   38  git status
   39  git push
   40  nano ~/.gitconfig
   41  git add .
   42  git commit
   43  git push
   44  nano ~/.gitconfig
   45  history > readme.md
