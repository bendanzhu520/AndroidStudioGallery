 Command line instructions
Git global setup

git config --global user.name "Administrator"
git config --global user.email "admin@example.com"

Create a new repository

git clone ssh://git@171.221.254.214:18083/meihuan/AndroidStudioGallery.git
git clone http://192.168.9.247:18081/meihuan/AndroidStudioGallery.git
cd AndroidStudioGallery
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder or Git repository

cd existing_folder
git init
git remote add origin ssh://git@171.221.254.214:18083/meihuan/AndroidStudioGallery.git
git remote add origin http://192.168.9.247:18081/meihuan/AndroidStudioGallery.git
git add .
git commit
git push -u origin master
