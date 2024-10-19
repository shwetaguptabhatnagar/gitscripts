Here’s the `commands.md` content in Markdown format without any code block comments:

```markdown
# Git Commands Documentation

## 1. Setting Up a Git Repository

```
mkdir gitscripts
cd gitscripts
git init
```

## 2. File Operations

### Viewing and Editing Files

```
cat hello.txt
vim hello.txt
```

### Creating New Files

```
touch hello1.txt
touch hello2.txt
```

## 3. Staging and Committing Changes

### Staging Files

```
git status
git add hello.txt
git add hello1.txt
```

### Committing Changes

```
git commit -m "committing hello.txt"
```

## 4. Configuring User Information

```
git config --global user.email "shwetagupta806@gmail.com"
git config --global user.name "shwetagupta"
```

## 5. Managing Files in the Repository

### Removing Files

```
rm hello.txt
git status
```

### Restoring Files

```
git restore hello.txt
```

### Unstaging Files

```
git rm --cached hello1.txt
git status
git restore hello1.txt
```

## 6. Branching

### Creating and Switching Branches

```
git branch
git checkout -b dev
git checkout master
git checkout dev
```

## 7. Viewing Commit History

```
git log
git log --oneline
```

## 8. Common Errors

```
git brach
git brancj
```

## Conclusion

This document provides a concise overview of essential Git commands for managing repositories, including setup, file operations, committing changes, user configuration, and branching.
```

You can save this text as `commands.md`. Let me know if you need any more adjustments!
