1. create environment
  conda create -n wineq python=3.7 -y
  conda activate wineq
2. created requirements.txt
3. install requirements
   pip install -r requirements.txt
4. template creation
   python3 template.py 
5. git init
6. dvc init
7. git init
8. dvc init
9. dvc add data_given/winequality.csv
10. git add .
11. git commit -m "intial commit"
12. git remote
13. git repo
14. git add . && git commit -m "updated readme with commands"
15. git remote add origin https://github.com/kananthk/mlops-winetesting.git
16. git branch -M main
17. git push -u origin main
18. dvc repro
19. dvc metrics diff
20. dvc metrics show