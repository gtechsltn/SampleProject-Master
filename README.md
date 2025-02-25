# SampleProject-Master

https://github.com/BehzadDara/SampleProject/tree/master

# Prepare
```
md D:\gtechsltn\SampleProject-Master\src
copy source to src folder
```

# Push code
```
cd D:\gtechsltn\SampleProject-Master
git init
git remote add origin https://github.com/gtechsltn/SampleProject-Master.git
git remote -v
git add .
git commit -m "SampleProject-Master"

git branch --set-upstream-to=origin/master
branch 'master' set up to track 'origin/master'.

git pull
git pull --allow-unrelated-histories
git push --set-upstream origin master
git push
```

## Try this
```
git pull origin main --allow-unrelated-histories
git merge origin origin/main
```

## Try other
```
git pull --allow-unrelated-histories origin master
git fetch

# Warning: RESET AHEAD
git reset --hard origin/master
```
