# 🌿 Git Branching Task

## 📸 Screenshot of the Task

![Task Screenshot](image.png)

---

## 📝 Explanation

### 1. Made Some Initial Commits in the `main` Branch

```bash
git commit -m "Initial commit"
```

### 2. Create three branches named `alpha, beta, prod`

```bash
git branch alpha
git branch beta
git branch prod
```

### 3. made 2 commits in each branch ( one example is given here )

```bash
git checkout alpha
git commit
git commit
```

### 4. made a `feature-1` branch from main branch

```bash
git checkout main
git branch feature-1
git checkout feature-1
git commit
```

### 5. made a hot-fix in main branch

```bash
git checkout main
git commit
```

### 6. merge the feature-1 branch in main branch

```bash
git merge feature-1
```

# 🔀 Pull Request Task

## 📸 Screenshots of the Task

### Below are the screenshots representing each step of the pull request process:

### 1. Made rules for feature branch

![alt text](image-2.png)

### 2. Made a branch `feature-1` and did some changes in it.

![alt text](image-8.png)

### 3. We can see the compare the changes made in feature-1 branch and create a pull request.

![alt text](image-4.png)

### 4. crate a pull request.

![alt text](image-5.png)

### 5. Merge the pull request.

![alt text](image-7.png)

### 6. branch is merged and can be deleted if needed.

![alt text](image-6.png)
