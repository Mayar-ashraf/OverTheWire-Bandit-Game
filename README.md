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
![Level 1](https://github.com/user-attachments/assets/2b6530ac-dc96-45c9-aefd-164a396a884e)


## Level 2
- **Commands Used:**
  ```bash
  cat ./-
  ```
- **Password Found:** 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
![Level 2](https://github.com/user-attachments/assets/9412aab0-b270-4e3a-96cc-9483c8093632)


## Level 3
- **Commands Used:**
  ```bash
  ssh bandit2@bandit.labs.overthewire.org -p 2220
  ls
  cat spaces\ in\ this\ filename
  ```
- **Password Found:** MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
![Level 3](https://github.com/user-attachments/assets/94f10540-4ba6-4533-831c-0eff96f12f99)


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
![Level 4](https://github.com/user-attachments/assets/2bcd30fd-097f-44ba-8f2f-0343efc28980)


## Level 5
- **Commands Used:**
  ```bash
  ssh bandit4@bandit.labs.overthewire.org -p 2220 
  find -type f | xargs file
  cat ./-file07
  ```
- **Password Found:** 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw 
![Level 5](https://github.com/user-attachments/assets/3f936fe5-d74e-48d0-b2da-ed25b310b368)


## Level 6
- **Commands Used:**
  ```bash
  ssh bandit5@bandit.labs.overthewire.org -p 2220
  find . -size 1033c ! -executable
  cat ./inhere/maybehere07/.file2
  ```
- **Password Found:** HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
![Level 6](https://github.com/user-attachments/assets/57d8f9c5-bdf1-4574-91f9-45c9de81c5b7)


## Level 7
- **Commands Used:**
  ```bash
  ssh bandit6@bandit.labs.overthewire.org -p 2220
  find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
  cat /var/lib/dpkg/info/bandit7.password
  ```
- **Password Found:** morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
![Level 7](https://github.com/user-attachments/assets/f1969851-2a30-4940-93d6-8259bf28109f)


## Level 8
- **Commands Used:**
  ```bash
  ssh bandit7@bandit.labs.overthewire.org -p 2220
  grep "millionth" data.txt
  ```
- **Password Found:** dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
![Level 8](https://github.com/user-attachments/assets/0888586a-ae0c-4ff6-8ca4-d3642dd120f7)


## Level 9
- **Commands Used:**
  ```bash
  ssh bandit8@bandit.labs.overthewire.org -p 2220
  sort data.txt | uniq -u
  ```
- **Password Found:** 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
![Level 9](https://github.com/user-attachments/assets/65d2281b-cf14-4cce-b95a-ca5d82134cb2)


## Level 10
- **Commands Used:**
  ```bash
  ssh bandit9@bandit.labs.overthewire.org -p 2220
  strings data.txt | grep "=*"
  ```
- **Password Found:** FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
![Level 10](https://github.com/user-attachments/assets/f52140da-34fa-4460-a148-e32937009529)


## Level 11
- **Commands Used:**
  ```bash
  ssh bandit10@bandit.labs.overthewire.org -p 2220
  base64 -d data.txt
  ```
- **Password Found:** dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
![Level 11](https://github.com/user-attachments/assets/3e03f6cf-7ba1-4e0b-963a-5341880adb93)


## Level 12
- **Commands Used:**
  ```bash
  ssh bandit11@bandit.labs.overthewire.org -p 2220
	cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'	

  ```
- **Password Found:** 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
![Level 12](https://github.com/user-attachments/assets/b481e319-083f-4650-a5ef-476f88821fc6)

