# Basic_GitHub
This note is to update a GitHub repository.

## Clone a GitHub repository
Nagivate to the reopsitory main page. 

Find "Clone with HTTPS" and copy the address such as;
https://github.com/XXXX/XXX.git

In the local terminal, navigate to the directory in which you want to download the GitHub contents. And then type ```git clone```
```
cd your_local_directory
git clone https://github.com/XXXX/XXX.git
```
The download will be completed.


## Download an updated directory from GitHub as `master`
### Download updated GitHub directory contents into your local directory
In the local terminal
```
cd your_local_directory
```
For example,
```
cd GitHub_files/smg
```
Download all files to your_local_directory (for example, all files in smg directory).
```
git pull origin master
```

### Make changes locally in the downloaded directory

I create a new directory in your_directory and create README file.
```
mkdir your_new_directory
cd your_new_directory
touch README.md
nano README.md
# Any description
# Press: control + X
# Type: Y
# Press: enter
```
For exmaple, I created smg/incubate/adventitious_virus since my new directory should be in "incubate" directory.


Check the changes you've made.
```
git status
```
This will display the changes in red.

### Upload your local changes to GitHub directory
Add the changes so that you can commit them, and check the status.
```
git add your_changes_in_red
git status
```
For exmaple, `git add adventitious_virus/`
Then, you'll see the changes in green.

Add a commit with your changes.
```
git commit -m "Your Own Comment"
```

Send your changes to your_directory as `master`.
```
git push origin master
```


