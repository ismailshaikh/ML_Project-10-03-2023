# ML_Project-10-03-2023
## This is End To End Machine Learning Project

### Adult_Censes_dataset_Machine_Learning
##### Ineuron Internship Project with Machine Learning Pipeline full Deployement from Scratch

## Software and Account Requirement:

1. [Github Account](http://github.com)
2. [VS Code IDE](https://code.visualstudio.com/download)
3. [GIT Cli](https://git-scm.com/downloads)


'''
Creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate adult_cences_dataset/
```
OR 
```
conda activate adult_cences_dataset
```

```
pip install -r requirements.txt
```

To Add files to git
```
git add .
```
OR  
'''
git  add <file_name>
'''
> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file


To Check the git status

'''
git status
'''

To check all version maintained by git
'''
git log
'''

To create version/commit all changes by git
'''
git commit -m message
'''

To send version/changes to github
'''
git push origin main
'''

To check remote url
'''
git remote -v
'''


BUILD DOCKER IMAGE
'''
docker build -t <image_name>:<tagname>
'''
> Note: image name for docker must be lowercase

To list docker image
'''
docker image
'''

Run docker image
'''
docker run -p 5000:5000 -e PORT=5000 <image ID>
'''

To Check running containers in docker
'''
docker ps
'''

to stop docker container
'''
docker stop <container_id>
'''

'''
python setup.py install
'''

