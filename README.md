version_1

python template.py

push to github  ------> 

git add .
git commit -m "folder structure added"
git push origin version_1

conda create -n cancer python=3.8 -y
conda activate cancer

pip install -r requirements.txt
pip install tensorflow==2.17.1

