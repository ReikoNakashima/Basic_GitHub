# Basic_GitHub

## Download an updated directory from GitHub as `master`
In the command line,
```
cd your_directory
```
For example,
```
cd smg
```
Download all files in your_directory.
```
git pull origin master
```
Create a new directory in your_directory and create README file.
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
cd ../
git status
```
This will display the changes in red.

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


