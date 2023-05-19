# DVC - DL - TF - AIOPS demo

## commands -

### create a new env

'''bash
conda create --prefix ./env python=3.7 -y
source activate ./env
'''

### init DVC

'''bash
git init
dvc init
'''

### create some empty files

'''bash
mkdir -p src/utils config
touch dvc.yaml requirement.txt params.yaml README.md
'''
