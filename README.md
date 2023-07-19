End To End Machine Learning Project
Set up project with Github
1. Data Ingestion
2. Data Transformation
3. Model Trainer
4. Model Evaluation
5. Model Deployment

CI/CD pipelines - Github actions
Deployment - AWS
===========================================

conda create -p venv python==3.8 -y
conda activate venv/

git init
git add README.md
git commit -m "this is my first commit"
git status
git branch -M main
git remote add origin https://github.com/amsowmya/Generic_E2E_MLProject.git
git remote -v
git config --global user.name "amsowmya"
git config --global user.email soumya.pdit@gmail.com
git push -u origin main
git pull
==============================
setup.py : Building our application as a package itself
-e . : # this will automatically trigger the setup.py file