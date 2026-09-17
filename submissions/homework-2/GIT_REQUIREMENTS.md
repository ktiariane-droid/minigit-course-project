# Homework 2 — Part 2 Submission

Student name: Ariane Kouame

GitHub username:

## 1. Git Command Observations

| Command or workflow | What did you observe? | What was the user trying to accomplish? | What problem or risk did it address? |
|---|---|---|---|
| 1.git status |Displayed the current branch and which files were modified, staged, or unstaged.  |The user wanted a quick overview of the current state of the working directory before deciding what to do next  |Prevents committing the wrong files, forgetting to stage something, or losing
track of unsynced changes with the remote.  |
| 2.git diff |Showed line-by-line changes made to files in the working directory that had not yet
been staged.  |The user wanted to review exactly what content had changed before deciding
whether to stage it.  |Prevents accidentally staging or committing wrong edits, typos  |
| 3.git add <file> followed by git diff --staged | git add moved specific changes into the staging
area; git diff --staged then showed only the changes that were staged and ready to be
committed. |The user wanted to select exactly which changes would go into the next commit,
and confirm that selection before committing.  | Shows the risk of committing unrelated or
incomplete changes together. |
| 4. git commit -m "<message>" followed by git log --oneline -3 |The commit created a
permanent snapshot with a descriptive message; git log --oneline -3 then listed the most recent
commits with their short IDs and messages.  |The user wanted to save a meaningful checkpoint
of their work and verify it was recorded correctly in the project history. || Prevents loss of work,
supports collaboration by giving teammates a clear history of what changed and why, and allows
reverting to a specific point if needed.  |

## 2. User Needs

### UN-GIT-01 — Short descriptive title

> Seeing the current state

### UN-GIT-02 — Short descriptive title

> Reviewing Changes Before Saving

### UN-GIT-03 — Short descriptive title

>Selecting What gets saved Together 

## 3. User Requirements

| ID and short title | User requirement | Source user need | Rationale |
|---|---|---|---|
| UR-GIT-01 |A developer shall be able to see a list of which files are changed, staged, or untracked at any point, without it affecting the files themselves  | UN-GIT-__01_ |A developer needs a way to quickly check what's changed in their project before doing anything else, because it's easy to forget which files you edited or accidentally leave something out when you go to save your work.  |
| UR-GIT-02 |A developer shall be able to see the exact line changes in a file that hasn't been staged yet, before deciding whether to include it.  | UN-GIT-_02__ | A developer needs a way to look at exactly what lines were changed in a file before saving them, because it's easy to miss a typo or accidentally leave in something you didn't mean to change. |
| UR-GIT-03 |A developer shall be able to choose only some of the changed content to include in the next save, without affecting the rest.  | UN-GIT-03___ | A developer needs a way to pick and choose which changes get saved together, because if you just save everything at once, your changes end up mixed together and it's hard to tell later what belonged to what. |
| UR-GIT-04 | A developer shall be able to view just the changes that have been selected so far, separately from anything not yet selected, before finalizing them. | UN-GIT-__04_ | A developer needs a way to double-check exactly what they picked before making it permanent, because it's easy to think you selected the right stuff and then find out later you missed something. |

