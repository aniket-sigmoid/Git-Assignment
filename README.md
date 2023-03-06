# Git-Assignment

Steps

1. Create a new repository in Github and cloned it in local

```
Used GitHUB-WEB for creating repo and terminal for cloning repo in local
```

2. Add a commit to main branch after making the skeleton of funcions

```
git add .
git commit -m "1st commit to main branch"
git push origin main
```

3. Create a feature-branch-1 branch from the main

```
git checkout -b feature-branch-1
```

4. Add a commit to feature-1 branch

```
git add .
git commit -m "added some code to 1st feature branch"
git push origin feature-1
```

5. Add a commit to local main branch 

```
git checkout main
git pull origin feature-1

```

6. Create another feature-branch-2 branch from local main

```
git branch feature-branch-2
```

7.Did some code change & Add a commit to feature branch then local main branch 

```
git add .
git commit -m "added some more code to feature branch 2"
git push origin feature-branch-2
git checkout main
```

8. Merge feature-branch-1 to main and then to origin main

```
git merge feature-1
git push origin main
```

9. Merge feature-branch-2 to main

```
git checkout main
git merge feature-branch-4
git push origin main
```
10. Follow the same procedure for any more branches made

11. Delete feature-1 and feature-2 branches from local main and also origin main

```
git branch -d feature-branch-1 feature-branch-2 
git push origin --delete efature-branch-1 feature-branch-2 
```

12. History Graph

![History Graph](Screenshot%202023-02-10%20at%207.11.32%20PM.png)
