"# Assignment 07: Git Workflow" 
## Student Name 
Cunzheng Dong
## Repository 
cse632-0526 
## Branch Name 
feature/cunzheng-dong-assignment-07 
## Commands Practiced 
- git clone 
- git remote -v 
- git config user.name 
- git config user.email 
- git checkout -b 
- git status 
- git add 
- git diff --staged 
- git commit 
- git push 
- git fetch 
- git merge 
- git log 
- git rev-parse HEAD 
## Directories Created 
- assignment-07/ 
- assignment-08/ 
- final_project/ 
## Git Remote Output 
Paste or summarize your `git remote -v` output here. ## Git Status Output 
origin git@github.com/cse632-0526.git (fetch)
origin git@github.com/cse632-0526.git (push)
Paste or summarize your `git status` output here.
On branch feature/cunzheng-dong-assignment-07
Changes to be committed:
new file: assignment-07/cunzheng-dong-git-workflow.md
## Pull Request URL 
https://github.com/shibainuinbos/cse632-0526/pull/1
## Latest Commit Hash 
56a55c24e771f1cd73647fed9ceb4bc33bd856f8
## Merge Conflict Summary 
I created two branches that modified the same line in README.md. When merging the second branch with the updated main branch, Git produced a merge conflict. I manually edited the README.md file to keep the correct final title, removed the conflict markers, staged the file, committed the resolution, and pushed the updated branch.
## Reflection 
This assignment helped me understand the complete Git workflow used in collaborative software development. I practiced creating branches to isolate work and learned how staging allows selective tracking of file changes before committing. I also learned how commits create checkpoints in project history and how pushing sends local work to GitHub. Creating a pull request showed me how code reviews and collaboration work in real projects. The merge conflict exercise taught me how Git detects conflicting changes and how to manually resolve them safely. I also practiced reviewing staged changes using git diff --staged and checking repository status frequently with git status. Overall, the assignment improved my confidence using Git commands in a real workflow.