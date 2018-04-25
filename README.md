# C++ Introduction Exercises

You can do this exercises (they are not mandatory) to practice what we've seen at class. I recomend doing them since you'll
need to do other more complicated mandatory and hopefully fun ones.

* **Exercise:** write a function that takes and array of ints and a int value and obtains all array values times the given value. The original array is modified and the function returns void
* **Exercise:** as before but this time the original array is not modified. The function returns a new array.
* **Exercise:** Write a program that reads in a sequence of characters, and determines whether
   its parentheses, braces, and curly braces are "balanced."  Hint:  for left
   delimiters, push onto stack; for right delimiters, pop from stack and check
   whether popped element matches right delimiter.
* **Exercise:** implement a queue using two stacks.

# GitHub
**Git** is a professional tool for keeping track of your code (a version control system) and GitHub is a platform that allows
to store your repositories in the cloud and share your code with others. GitHub (like GitLab, Bitbucket) are tools for team
working.

To hand-in your exercises you'll need to push your code to your repository. But before doing so you should add a file named 
".gitignore" so that git does not save unwanted files (like compiled files) in the repository. You can use the web
https://www.gitignore.io/ to create the file.

The following code can help you to push your exercises:
```
git init
git add .
git commit -mm "first commit"
git remote add origin https://github.com/DiscreteMathematicsT16-17/<your repository name>
git push -u origin master
```

