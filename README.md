## End to End Machine Learning Project

### Agenda

- 1.Create environment
      - conda create -p venv python==3.8
      - conda activate venv/
- 2.Clone git Repo
      - git init
      - git add README.md
      - git commit -m "first commit"
      - git branch -M main
      - git remote add origin https://github.com/SatK-        ds2020/MLops-Project1.git
      - git push -u origin main 
- 3.Add .gitignore file at github repo with python as choosen template and commit.
- 4.git pull to sync remote repo with local.
- 5.create setup.py (help application to written as package) & requirement.txt
- 6.Added project information in setup.py along with get requiremnt function to install packages from requirements.txt 
- 7.libraries and packages are added in requirement.txt with _e . to trigger setup.py to build package
- 8.Src folder is created, all the code will go there to build package