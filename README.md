# Pushing to Github from Jupyter

## Git in the terminal

### Step 1

Set up name & email in git by running <br>
<br>
$ git config --global user.email "you@example.com" <br>
$ git config --global user.name "Your Name"

### Step 2

Create new Repo in Github and clone in Jupyter <br>
$ git clone https://github.com/OierGman/Learning_C.git <br>
<br>
<details>
<summary>Output</summary>
<br>
Cloning into 'Learning_C'... <br>
warning: You appear to have cloned an empty repository.
</details>

### Step 3

Copy notebooks to the recently created repo Learning_C <br>
This example: <br>
<br>
$ cp NOS/Learning_C/dataTypeSize.c Learning_C/ <br>
$ cp NOS/Learning_C/dataTypeSize.exe Learning_C/ <br>
$ cp NOS/Learning_C/helloworld.c Learning_C/ <br>
$ cp NOS/Learning_C/helloworld.exe Learning_C/ <br>
$ cp NOS/Learning_C/inputoutput.c Learning_C/ <br>
$ cp NOS/Learning_C/inputoutput.exe Learning_C/ <br>
<br>
Check that all noetbooks exist in repo by: <br>
$ ls <br>

### Step 4

Tell local git client to track files <br>
$ git add dataTypeSize.c <br>
$ git add dataTypeSize.exe <br>
$ git add helloworld.c <br>
$ git add helloworld.exe <br>
$ git add inputoutput.c <br>
$ git add inputoutput.exe <br>
<br>
Check which files are being tracked <br>
$ git status <br>

### Step 5

commit tracked files to Repo (Learnin_C) <br>
$ git commit -m " *insert commit message* " <br>

### Step 6

Push all tracked files to Repo (Learning_C) <br>
$ git push <br>
<br>
<details>
<summary>Credentials</summary>
<br>
Username for 'https://github.com': OierGman <br>
**Support for password authentication was removed on August 13, 2021**. <br>
Password for 'https://OierGman@github.com': <br>
Create access token: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
</details>

Markdown Guidance : https://www.markdownguide.org/basic-syntax/
