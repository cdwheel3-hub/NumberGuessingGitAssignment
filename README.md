\# Number Guessing Game — Git Assignment



\## Project Overview



This project is a Java number guessing game used to practice Git version control and collaborative software development workflows. The project uses Gradle to build and test the application.



\## Git Operations and Lessons Learned



\### Branching and Merging



I learned how to create and switch between branches to develop features independently without immediately changing the main codebase. I practiced merging feature branches into the `dev` branch and resolving conflicts when different branches modified the same sections of code.



\### Rebasing



I used `git rebase` to update feature branches with changes from `dev`. Rebasing allowed me to replay feature commits on top of newer commits, creating a more linear history. I also learned how to resolve conflicts during a rebase and continue using `git rebase --continue`.



\### Squashing Commits



I practiced interactive rebasing to squash four commits from `feature3` into a single commit named `Add hint system to show proximity after 3 attempts`. This demonstrated how to simplify commit history while preserving the completed feature.



\### Cherry-Picking



I used `git cherry-pick` to apply the hotfix for the random number generator directly to `main` without merging the entire `hotfix` branch. I then merged `main` into `dev` to incorporate the fix into the development branch.



\### Resolving Merge Conflicts



I learned how to identify Git conflict markers and manually combine changes from different branches. The most challenging conflicts involved integrating the hint system with the maximum-attempts functionality while preserving the ability to quit the game.



\### Testing and Verification



After resolving conflicts and completing important Git operations, I used `./gradlew.bat clean build` to verify that the Java project compiled and passed its automated tests. I also used `git status` and `git log --oneline --graph --decorate` to verify branch states and commit history.



\## Conclusion



This assignment helped me understand how Git supports parallel development, how different integration techniques affect commit history, and why testing is important after combining changes. I gained practical experience with branching, merging, rebasing, squashing, cherry-picking, and conflict resolution.

