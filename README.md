# How-to-upload-your-project-to-GitHub

**1. Open the Terminal and move to project**
```
cd /yourProject
```

**2. Create Git**
```
git init
```

**3. add all file to Git**
```
git branch -M main
```
```
git add .
```

**4. Add mail, usernam github**
```
git config --global user.email "yourmail@gmail.com"
git config --global user.name "Your Github username"
```

**5.First commit**
```
git commit -m "Initial commit: push project to GitHub"
```

**6. Connect local to repository github**
```
git remote add origin https://github.com/username/YourProject.git
```

**7. push**
```
git push origin main
```

**If have change in Repository in Github**
```
git fetch origin
```
```
git add .
```
```
git rebase --continue
```
```
git push origin main
```



