# repo2image
conda env created based on https://repo2docker.readthedocs.io/

After intalling jupyter-repo2docker all that needs to be done is to :
 1. jupyter-repo2docker  --no-run  --user-name=jovyan  --image=<image repo/imagename:tag> <repo link>
 2. docker push the image 
 3. use the image in your juypterhub 
 Ex:  jupyter-repo2docker  --no-run  --user-name=jovyan  --image=costache2mihai/adsmlr2d:05.01.23 https://github.com/Mihai-CMM/repo2image.git
 
