<!-- slides.md -->

# GitHub Bootcamp

---

## How to initialise a new repository

```
mkdir mon_projet
cd mon_projet
git init

git add --all
git commit --message
Git push
```

---

## How to review changes

Si on constate des modifications avec 'git status', il est possible de les inspecter avec 'git diff' : 

```
git diff
git diff <file_name>
```

---

## How to commit changes

```
git status
git add --all
git commit -s --m "A meaningful message about this change"
```

ou

```
git add <fichier_modif>
```

---

## Create a new branch

```
git branch <branch_name>
git checkout <branch_name>
```

---

## Work on a branch

```
git checkout <branch_name>
```

---

## Merge branch on main

```
git checkout main
git diff main..<branch_name>
git merge <branch_name>
```

---

## Delete a branch

```
git branch --delete <branch_name>
```

---

## Pushing changes to remote

```
git push <remote> <branch>
git push origin main
```

---


## Happy Hacking