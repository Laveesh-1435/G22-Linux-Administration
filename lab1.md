# Experiment 1

Use the touch command to create sets of empty practice files to use during this lab. 
In each set, replace X with the numbers 1 through 6. 
Create six files with names of the form songX.mp3, snapX.jpg, filmX.avi. 
Create three subdirectories for organizing your files, and name the subdirectories friends, family, and work. Use a single command to create all three subdirectories at the same time.

---

## Approach

### 1) Creating multiple files 
The `touch` command with **brace expansion** is used to create multiple files efficiently.

### Syntax
```bash
touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi
```

---

### 2) Creating multiple directories
he `mkdir` command is used to create multiple directories in one go.

### Syntax
```bash
mkdir friends family work
```
