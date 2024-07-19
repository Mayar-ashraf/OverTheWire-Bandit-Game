# OverTheWire Bandit Solutions
## Level 0
- **Commands Used:**
  ```bash
  ssh bandit0@bandit.labs.overthewire.org -p 2220
  ```
- **Password Found:** bandit0

![Level 0](https://github.com/user-attachments/assets/182a3a3f-0d8f-4cb1-b853-adbdec23af33)


## Level 1
- **Commands Used:**
  ```bash
  ssh bandit1@bandit.labs.overthewire.org -p 2220
  cat readme
  ```
- **Password Found:** ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5Ifexit
<Screenshot>

## Level 2
- **Commands Used:**
  ```bash
  cat ./-
  ```
- **Password Found:** 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
<Screenshot>

## Level 3
- **Commands Used:**
  ```bash
  ssh bandit2@bandit.labs.overthewire.org -p 2220
  ls
  cat spaces\ in\ this\ filename
  ```
- **Password Found:** MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
<Screenshot>

## Level 4
- **Commands Used:**
  ```bash
  ssh bandit3@bandit.labs.overthewire.org -p 2220
  ls
  cd inhere
  ls -la
  cat ...Hiding-From-You
  ```
- **Password Found:** 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
<Screenshot>

## Level 5
- **Commands Used:**
  ```bash
  ssh bandit4@bandit.labs.overthewire.org -p 2220 
  find -type f | xargs file
  cat ./-file07
  ```
- **Password Found:** 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw 
<Screenshot>

## Level 6
- **Commands Used:**
  ```bash
  ssh bandit5@bandit.labs.overthewire.org -p 2220
  find . -size 1033c ! -executable
  cat ./inhere/maybehere07/.file2
  ```
- **Password Found:** HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
<Screenshot>

## Level 7
- **Commands Used:**
  ```bash
  ssh bandit6@bandit.labs.overthewire.org -p 2220
  find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
  cat /var/lib/dpkg/info/bandit7.password
  ```
- **Password Found:** morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
<Screenshot>

## Level 8
- **Commands Used:**
  ```bash
  ssh bandit7@bandit.labs.overthewire.org -p 2220
  grep "millionth" data.txt
  ```
- **Password Found:** dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
<Screenshot>

## Level 9
- **Commands Used:**
  ```bash
  ssh bandit8@bandit.labs.overthewire.org -p 2220
  sort data.txt | uniq -u
  ```
- **Password Found:** 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
<Screenshot>

## Level 10
- **Commands Used:**
  ```bash
  ssh bandit9@bandit.labs.overthewire.org -p 2220
  strings data.txt | grep "=*"
  ```
- **Password Found:** FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
<Screenshot>

## Level 11
- **Commands Used:**
  ```bash
  ssh bandit10@bandit.labs.overthewire.org -p 2220
  base64 -d data.txt
  ```
- **Password Found:** dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
<Screenshot>

## Level 12
- **Commands Used:**
  ```bash
  ssh bandit11@bandit.labs.overthewire.org -p 2220	

  ```
- **Password Found:** 
<Screenshot>
