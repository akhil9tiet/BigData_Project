# BigData_Project
Code Repository for Big Data

Setup guide:
0. ```git chekout master```, ```git pull origin master```, IGNORE THIS STEP IF YOU ARE SETTING UP THE REPO
1. Open up gitbash and navigate to the directory where you want to save the file
2. ```git clone https://github.com/akhil9tiet/BigData_Project.git ```
3. Create a new branch and name it same as the collaborator
  * to create a new branch on github (Click on branch name and then create a new branch)
  * on gitbash ```git checkout <branchname>```
4. Add/edit/delete files in your branch.
5. ``` git add <<<filename>>>```
6. ``` git commit -m "{{Logical commit related to one idea only}}``` PLEASE DO NOT POLLUTE THE COMMIT HISTORY. THE COMMIT MESSAGE SHOULD BE LOGICAL AND SHORT. IT SHOULD BE SIMPLE ENOUGH FOR EVERYONE TO UNDERSTAND.
Please refer a small blog for commit message naming convention. [Here](https://github.com/erlang/otp/wiki/Writing-good-commit-messages)
7. ```git push origin <branchname>```
8. Create a pull request with branch "master" naming all the other collaborators people as reviewers.
9. Merge with Maseter. MERGE ONLY IF ATLEAST 2 COLLABORATORS HAVE AGREED ON THE PULL REQUEST.
10. (ALSO STEP 0.)```git checkout master``` ```git pull origin master``` THIS IS VERY IMPORTANT OTHERWISE CODE CONFLICT MAY OCCCUR
