# git-practice

Welcome! This is a repository you can safely make commits to and play around with to learn how to use git and github

Add some test text to prove I can edit the file on the master branch

Now add some stuff to the new_markdown branch. Had lots of fun trying to commit due to already having used git on this machine and it picking up ssh keys and another git username...solution was to use 

get remote set-url origin https://<username>@github.com/<username>/git-practice.git

Without doing this you get username errors or git defaults to ssh and uses the macs credential helper... 

See: https://stackoverflow.com/questions/39944469/my-old-username-is-still-in-use/39944557#39944557
and https://help.github.com/en/articles/updating-credentials-from-the-osx-keychain

Very frustrating!