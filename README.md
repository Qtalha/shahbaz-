Shopizer project please install java 11 on node 1.
Fork this into your remote repo.
Give it a name of your choice--- .
Git clone into your system then in terminal type 'code . '.
Then add new file named 'jenkinsfile'.
Now you have two ways to access git one from terminal & other one is from V.S code itself , 
result of both will be the same as your are in same folder in both of the ways .
Git branch 'demo' any name of your choice the checkout in that branch,
you can simply do both with one command 'git checkout -b "demo'.
Then git add .  
After that git commit .
Then once your file is commited now we will push into the remote repo i.e github repo 
Execute the command git push origin demo .
Then the file which you have written will be seen in jenkins file in remote repo. 
then just open jenkins choose pipeline option .
After that you will see two options choose pipeline script from git and, 
then paste your git repo into it (the link which you will copy from the option 'code'.
Then write name of your branch .
Then specify the file in which the pipeline script is present i.e jenkinsfile.
Then apply 
Save and build now.
