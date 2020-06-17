# This file contains instructions on how to branch and still retain files in master especially in your own repo.
## I tested it on my repo don't know if it will work elsewhere

##### Step 1


''' 
create a different branch this case i named it 2.
'''


Then i ran command below on terminal, make sure you backup whats on your local folder because this command will overwrite anything on that folder.


    $sudo git pull origin 2 --allow-unrelated-histories

##### Step 2

Now you have everything on that repo on your local computer.


Then you want to change the branch since it will be pointing at master on your local machine .


To see all the branches run:


    $git checkout

##### Step 3

To change to a specific branch, eg branch 2 run:


    $git checkout 2

##### Step 4

Now you can start working on that branch and be able to push without interfering with master branch.


You will be pushing to :


    $git push -u origin 2
