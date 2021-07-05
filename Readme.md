creat env
conda create -n wineq python=3.7 -y
activate env
conda activate wineq
create a req file
install the req file
pip install -r requirements.txt
down load the data and add to the folder
after adding the data

git init
dvc init
dvc add data_given/winequality.csv    -->to track the data
git add .
git commit -m "first commit"

###
python -m pip install .
   24  conda activate Anaconda3
   25  conda activate wineq
   26  pip install -r requirements.txt
   27  dir
   28  python template.py
   29  python template.py
   30  git init
   31  dvc init
   32  dvc add data_given\winequality.csv
   33  dvc add data_given/winequality.csv
   34  git add .
   35  git commit -m "first commit"
   36  git add . &&  git commit -m "update Readme.md"
   37  git remote add origin https://github.com/Arju-cmd/simple-dvc-demo.git
   38  git branch -M main
   39  git push origin main