# OS-Linux-commands-Shell-scripting

Operating systems Lab exercise.

# EX - 1 Linux commands-Shell scripting:

Linux commands-Shell scripting

## AIM :

To practice Linux Commands and Shell Scripting.

## DESIGN STEPS :

### Step 1 :

Navigate to any Linux environment installed on the system or installed inside a virtual environment like virtual box/vmware or online linux JSLinux (https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192) or docker.

### Step 2 :

Execute the following commands

### Step 3 :

Testing the commands for the desired output. 

## COMMANDS :

### Create the following files file1 as follows :
```
mkdir exp
cd exp
cat>f1
```
### OUTPUT :

![Screenshot from 2024-03-04 21-37-14](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/e2ec527d-aff9-4bf3-8386-6ac0dddf3e8b)

### MORE :
```
cat f1|more
```
### OUTPUT :
![Screenshot from 2024-03-04 21-40-54](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/14031677-942e-47a1-bdfb-2cb253db6934)

### DISPLAY :
```
ls
```

### OUTPUT :

![Screenshot from 2024-03-04 21-44-27](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/bd319111-7960-4da9-b26f-947d690c61ac)

### LESS :
```
cat f1|less
```
### OUTPUT :
![Screenshot from 2024-03-04 21-46-28](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/0f123fde-8d4a-45bc-8b55-ab1d183b7c93)


### TAIL :
```
tail f1
```
### OUTPUT :
![Screenshot from 2024-03-04 21-50-27](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/93ec1d18-9324-46dd-ad58-07933a873db9)

### HEAD :
```
head f1
```
### OUTPUT :

![Screenshot from 2024-03-04 21-52-29](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/2644ecca-8c79-4a2b-9976-f36623211436)

### SORT :
```
sort f5
```
### OUTPUT :
![Screenshot from 2024-03-04 22-18-10](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/d9837910-c042-4663-938b-8afbb979ad56)


### UNIQ :
```
uniq f5
```
### OUTPUT :
![Screenshot from 2024-03-04 22-19-50](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/20084ef9-704d-4cb3-a006-c69ae2e8a853)

### SORT & UNIQ :
```
sort f5 | uniq
```
### OUTPUT :
![Screenshot from 2024-03-04 22-21-46](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/fbbe429f-6fc8-4975-b30a-b9385e99366d)


### awk :
```
cat f6 |awk '{print $1}'
```
### OUTPUT :

![Screenshot from 2024-03-04 22-29-10](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/629a38b5-d1fe-4686-a6d6-339726df626b)

### DISPLAY ALL :
```
ls -l
```
### OUTPUT :
![Screenshot from 2024-03-04 22-32-48](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/f92132fe-057b-4c2a-80d8-bc567f5638d2)

### SORT.OUT :
```
ps | sort>f1sort.out
```
### OUTPUT :
![Screenshot from 2024-03-04 22-49-28](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/ec091146-7ac3-4140-b5a3-a3697501dc6b)

### F1.OUT :
```
ps | sort > f1.out
```

### OUTPUT :
![Screenshot from 2024-03-04 22-53-27](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/fb88f9f4-08e8-498b-b6c3-6791684af3ac)

### SORT - FILE.OUT :
```
ps | sort > saveetha.out
ls
```
### OUTPUT :
![Screenshot from 2024-03-04 22-56-52](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/bca6bae0-6493-4f26-8431-28dd602eeb35)

### FILE.OUT :
```
cat saveetha.out
```

### OUTPUT :
![Screenshot from 2024-03-04 22-59-29](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/8ef6a0b7-b9bd-4e76-a7d3-031fd944912b)

### ECHO :
```
echo Saveetha Engineering College >> f3
cat f3
```
### OUTPUT :

![Screenshot from 2024-03-04 23-03-24](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/86163849-80c5-4b82-90f8-c4a92ed74475)

###  STOP :
```
cat<<stop>here.check.txt
```
### OUTPUT :
![Screenshot from 2024-03-04 23-07-29](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/ddd500ff-7faa-4b85-af8b-83d8ba13478b)


### START :
```
cat<<start>f5
```
### OUTPUT :

![Screenshot from 2024-03-04 23-09-39](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/6b742a62-bf1b-460e-902f-74a99b027b8f)

###  VALUE :
```
x=7
echo $ x
```
### OUTPUT :

![Screenshot from 2024-03-04 23-15-01](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/efe7d810-ccaa-423d-b333-a526dfb12c55)

### DECLARE :
```
declare x=7
let y=4
set z=6
echo $x $y $z
```
### OUTPUT :
![Screenshot from 2024-03-04 23-17-22](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/37f72b4c-18fa-4b43-9b80-59eea64a617b)

### EXPORT :
```
export z
echo $x $y $z
```
### OUTPUT :
![Screenshot from 2024-03-04 23-19-49](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/81a39c58-5316-4b8b-b9c8-4bd3604b9c79)

### ADD VALUE :
```
expr $x+$y
```
### OUTPUT :
![Screenshot from 2024-03-04 23-22-05](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/afef756c-6e48-4049-ae86-dcd922e7fad7)

### MULTIPLY VALUE :
```
expr $x\*$y
```
### OUTPUT :
![Screenshot from 2024-03-04 23-27-13](https://github.com/Abrinnisha6/OS-Linux-commands-Shell-script/assets/118889454/7f2ae117-8908-4bb2-99d2-e563123e98a3)

## RESULT :

The Commands are executed successfully.
























