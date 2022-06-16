# Machine-Learning-Project

Software and account Requirement:

1.  [Github Account] (https://github.com/)
2.  [Heroku Account] (https://dashboard.heroku.com/apps)
3.  [VS Code IDE] (https://code.visualstudio.com/download)
4.  [GIT cli]  (https://cli.github.com/)
5.  [Git Documentation] (https://git-scm.com/docs/gittutorial)


--create virtual env in your folder:
'''
create conda -p venv python==3.8 -y
'''
----------------------------------------------------------------
activate your environment
'''

conda activate venv
or 
conda activate venv/
'''
----------------------------------------------------------------
install Requirement
'''
pip install -r requirements.txt
'''
--------------
 To add files
 '''
 git add .
 
  OR
  
 git add <filename>
 '''
 Note: To ignore file or folder from git we can write name of file /folder in .gitignore file
 '''
 To check status:
 '''
 git status


 To check all versions maintained by git
 '''
 git log
 ----------------------------------------------------------------
 To create version/commit all changes by git
 '''
 git commit -m "message"

 To send version/changes to github.com/
 '''
 git push origin main
 
 --------------
 To check remote url
 '''
 git remote -v
 

To setup CI/CD pipeline with HEROKU we need 3 information
While creating new app in heroku put dashes between words

1. HEROKU_EMAIL = nesibegl@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-with-docker


BUIL DOCKER IMAGE`
```
docker build -t <image_name>:<tagname> .

```
> Note: Image bane for docker must be lowercase

To list docker images

'''
docker image
'''

Run docker image

'''
docker run -p 5000:5000 -e PORT=5000 <imageid>

To check running docker container

'''
docker ps
'''

To stop docker container

'''
docker stop <containerid>

'''







