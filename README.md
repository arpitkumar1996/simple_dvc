 
   1 conda create -n wineq python=3.7 -y
   2 conda activate wineq


   3 touch requirements.txt

   4 history
 

   5 python template.py

   6 mkdir data_given

   7 git init

  8 dvc init

  9 git add .

  10 git commit -m "first commit"

  11 git remote add origin <github repo url>
 
  12 git branch -M main

  13 git branch

  14 git push origin main

  15 tox command -

      tox
      for rebuilding -

      tox -r 
  16 pytest command

      pytest -v
   17    setup commands -

      pip install -e . 
   18 build your own package commands-

      python setup.py sdist bdist_wheel
  