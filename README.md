create env

'''bash
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
'''

created a requirement file

installed the requirement file
'''bash
pip install -r requirements.txt
'''

git init

dvc init

dvc add data_given/winequality.csv


git add .

git commit -m "first commit"

update master to main branch

add remote repository