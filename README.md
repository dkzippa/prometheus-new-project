# prometheus-new-project
Prometheus DevOps та Kubernetes

- `git config --global user.name "..."`
- `git config --global user.email "..."`
- `git config --global init.defaultBranch "main"`
- `mkdir prometheus-new-project`
- `cd prometheus-new-project`
- `git init`
- `git remote add origin git@github.com:dkzippa/prometheus-new-project.git`
- `git checkout main`
- `touch README.md`
- `git add .`
- `git commit -m 'init'` 
- `git push`
- `git checkout -b "development"`
- `git add .`
- `git commit -m "development branch"`
- `git push --set-upstream origin development`
- `git checkout main`
- `git fetch`
- `git merge development`
- `git add .`
- `git commit -m "merge development into main"`
- `git push`
