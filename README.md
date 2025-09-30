# datafun-07-ml
project:
  name: datafun-07-ml
  description: Predictive Analytics & Machine Learning project (Module 7)
  author: ABDELLAH BOUDLAL
  repo: https://github.com/Aboudlal/datafun-07-ml

requirements:
  - jupyterlab~=4.2
  - numpy~=2.1
  - pandas~=2.2
  - scipy~=1.14
  - matplotlib~=3.9
  - seaborn~=0.13
  - pyarrow==21.0.0

gitignore:
  - __pycache__/
  - .ipynb_checkpoints/
  - .venv/
  - .DS_Store
  - Thumbs.db
  - .vscode/
  - .idea/
  - *.log

setup:
  clone:
    - git clone https://github.com/Aboudlal/datafun-07-ml.git
    - cd datafun-07-ml
  venv:
    - py -m venv .venv
    - .\\.venv\\Scripts\\activate   # Windows
    - source .venv/bin/activate    # Linux/Mac
  install:
    - pip install --upgrade pip setuptools wheel
    - pip install -r requirements.txt

run:
  - jupyter lab
