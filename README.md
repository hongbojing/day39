# day39
LOL, I used this file to prictise the git reset for a while, really fun.

Make a brief summary:

1 from unstage to stage:
>>> git add .

2 from stage to commit:
>>> git commit -m'msg'

3 to change the previous commit msg:
>>> git commit --amend -m'new msg'

4.1 move the state from commit to stage
>>> git reset --soft HEAD^

5 move the state from stage to un-stage
>>> git reset HEAD file_name

4.2 move state from commit to unstage && undo the changes you made to the files
>>> git reset --hard HEAD^
