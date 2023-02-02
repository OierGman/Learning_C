# Pushing to Github from Jupyter

## Git in the terminal

### Step 1
Set up name & email in git by running <br />
<br />
$ git config --global user.email "you@example.com" <br />
$ git config --global user.name "Your Name"

### Step 2

$ git clone https://github.com/OierGman/Learning_C.git <br />
<br />
<details open>
<summary>Output</summary>
<br>
Cloning into 'Learning_C'... <br />
warning: You appear to have cloned an empty repository.
</details>

### Step 3
Copy notebooks to the recently created repo Learning_C <br />
<br />
$ cp NOS/Learning_C/dataTypeSize.c Learning_C/ <br />
$ cp NOS/Learning_C/dataTypeSize.exe Learning_C/ <br />
$ cp NOS/Learning_C/helloworld.c Learning_C/ <br />
$ cp NOS/Learning_C/helloworld.exe Learning_C/ <br />
$ cp NOS/Learning_C/inputoutput.c Learning_C/ <br />
$ cp NOS/Learning_C/inputoutput.exe Learning_C/ <br />
<br />
Check that all noetbooks exist in repo by: <br />
$ ls <br />

### Step 4
