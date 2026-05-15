Q.What is a branch in Git?
Branch in Git is Separate Workspace for working something else or trying new ideas without affecting the main project.
Branch in Git Are Mainly useful for fixing bugs, developing new features and try new ideas.
Commands:-
A) To Create Branch
git branch branchname

B) Delete Branch
git branch -d branchname

C) Rename Branch
git branch -m old-branchname new-branchname

D) Switch Branch
git checkout branchname/git switch branchname

E) Creating New Branch And Switching into that simultaneously
git checkout -b branchname

F) List Branch
git branch

Q.Why do we use branches instead of committing everything to main?
Branch is Separate Workspace for working something else or trying new ideas.
Suppose, We Want to create something new feature which might consists of bugs, if I worked and combined these changes to main branch, then my main branch may got affected, it might stop working or may crash.
So, it Is better to create new branch and after developing new feature in that branch merge it to main branch.

Q.What is HEAD in Git?
Head in Git, It Point to the latest change we are currenlty working or or we just finish the change.We Can check head status by doing git log command.

Q.What happens to your files when you switch branches?
While Switching from one branch to another branch it is always recommended that always commit the pending changes, to stop overwriting and losing the data furtther.

