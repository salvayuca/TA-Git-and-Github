1. Create a folder called git-basic. (__mkdir git-basic__)
2. cd into the git-basic folder. (__cd git-basic__)
3. Create a file called first.txt. (__touch first.txt__)
4. Initialize an empty git repository.
    (__git config --global user.name "salvayuca"__
    __git config --global user.email salvayuca88@gmail.com__
    __git init__)
5. Add first.txt to the staging area. (__git add first.txt__)
6. Commit with the message "adding first.txt". (__git commit -m "adding first.txt"__)
7. Check out your commit with git log. (__git log__)
8. Create another file called second.txt. (__touch second.txt__)
9. Add second.txt to the staging area. (__git add second.txt__)
10. Commit with the message "adding second.txt". (__git commit -m "adding second.txt"__)
11. Remove the first.txt file. (__git rm first.txt__)
12. Add this change to the staging area. (__git add .__)
13. Commit with the message "removing first.txt". (__git commit -m "removing first.txt"__)
14. Check out your commits using git log. (__git log__)
