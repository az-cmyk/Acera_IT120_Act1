git init -b main
git add .
git commit -m "Initial commit: add files"
git checkout -b YOURLASTNAME_B1
git add Profile.txt
git commit -m "B1: add birth place, religion, parents to Profile.txt"
git checkout main
git checkout -b YOURLASTNAME_B2
git add Education.txt
git commit -m "B2: add college and program to Education.txt"
git checkout main
git checkout -b YOURLASTNAME_B3
git add Background.txt
git rm Test.py
git commit -m "B3: add contact & address; remove Test.py"
git checkout main
git checkout -b YOURLASTNAME_B4
git add Readme.txt
git rm Test.py
git commit -m "B4: add git commands to Readme.txt; remove Test.py"
