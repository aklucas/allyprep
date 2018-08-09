# Git Instructions

- Check out a new branch.

  ```
  git checkout -b branch-name
  ```

- Work on the problems.

  > It's probably a good idea to "commit" your changes for each exercise (below). 
  
- Commit your work.

  ```
  git add . // This commits *all* your changes. You could also commit individually by replacing the "." with a file name.
  git commit -m 'This is what I did'
  ```

- When you're done with this branch's exercises, "push" the code to that branch on Github

  ```
  git push -u origin branch-name
  ```

- Then go to the repo on Github (github.com/aklucas/allyprep). You should see a yellow banner suggesting you make a Pull Request (PR).

- Click that banner, and complete making the pull request, then let us know, and we can review it. 

- We or you can then "merge" the request into the "master" branch (literally, in this case, called master)

- Locally, return to "master", and pull down the new master code.

  ```
  git checkout -b master
  git pull
  ```

- You should now be on your main branch with up-to-date code, ready to repeat the above.
  
