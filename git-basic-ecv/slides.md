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

## Pulling changes from remote

```
git pull <remote> <branch>
git pull origin main
```

---

# Lists with some content

- cats
- dogs
- birds

---

# Images with an image

![Image Alt Text](https://www.wfla.com/wp-content/uploads/sites/71/2023/05/GettyImages-1389862392.jpg?w=2560&h=1440&crop=1)

---

# Headers & Quotes with some content

## Subheading

> This is a quote.

---

# Code with some code

```python
print("Hello, world!")
```

---
## Happy Hacking