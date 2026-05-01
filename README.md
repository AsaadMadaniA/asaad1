def add(a, b):
    return a + b

def test_add():
    assert add(2, 3) == 5 

    C:\Users\ACER>e:

E:\>cd bsr
E:\bsr>git init
E:\bsr>git remote -v
E:\bsr>git remote add origin https://github.com/bskrmtech-code/bsr
E:\bsr>git config --global user.name bskrmtech-code
E:\bsr>git config --global user.mail bskr.mtech@gmail.com
E:\bsr>cd .github
E:\bsr\.github>cd workflows
E:\bsr\.github\workflows>type nul > bsr.yml
E:\bsr\.github\workflows>cd..
E:\bsr\.github>cd..
E:\bsr>git branch -M main
E:\bsr>git push -u origin main
E:\bsr>git add .
E:\bsr>git commit -m "hi"
E:\bsr>git push


. (git init)
6.	Create a README file. (echo "# My Git Repository" > README.md)
7.	Add the README file to the staging area. (git add README.md)
8.	Commit the changes with a meaningful message. (git commit -m "Initial commit with README file")
9.	Connect the local repository to the remote repository. (git remote add origin “your gihub repository url”)
10.	Push the committed changes to the remote repository. (git branch –M main, git push -u origin main)


git checkout -b MITS
echo "Changes made in MITS branch" >> README.md
git add README.md
git commit -m "Modified README in MITS branch"
git checkout main
git branch main
git merge MITS


git add .
git commit -m "Updated files"
git push origin main

import selenium
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
import time
driver=webdriver.Edge()
driver.get("http://facebook.com")
time.sleep(2)
print("EDGE opened successfully")
driver.quit()
