# Linux Navigation

## Where am I?

'''bash
pwd
'''

Shows the current directory
Example
'''

/home/anton/Documents
'''

---

## List files
'''bash
ls
'''

Lists files and folders

useful options:

'''bash
ls -l
ls -la
ls -R
'''

---

## Change directory

'''bash
cd Documents
cd ..
cd 

---

## Create

Create file:

'''bash
touch notes.txt
'''

Create directory:

'''bash
mkdir Projects
'''

---

## Copy

'''bash
cp file.txt copu.txt
cp file.txt Backup/
'''

---

## Move/Rename

Rename:
'''bash
mv old.txt new.txt
'''
Move:

'''bash
mv file.txt BAckup/

---

## Delete

Delete file:

'''bash
rm file.txt
'''

Delete directory:

'''bash
rm -r BAckup
'''

Be careful! rm delete permanently


## 📂 Absolute vs Relative Path

### Relative path

Current directory:

```text
/home/anton
```

Open file:

```bash
cat Documents/backup.txt
```

---

### Absolute path

Works from anywhere:

```bash
cat /home/anton/Documents/backup.txt
```

---

### Remember

- **Absolute path** starts with `/`
- **Relative path** starts from your current directory
- `..` means "go one directory up"
- `.` means "current directory"

## 🧭 Working with Relative Paths

Example:

Current directory:

```text
/home/anton/Documents
```

File location:

```text
/home/anton/Music/song.mp3
```

Relative path:

```bash
../Music/song.mp3
```


'''bash
