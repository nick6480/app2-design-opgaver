<h1>Notes<h1>

<h2> Task 1 <h2>
When using git add "filename" it stages the file for commit, can also use git add . to stage all files

When using git status it stages files to be commited, with the ability to unstage them by using git restore --staged file

```mermaid

graph TD;
    A[Working Directory] -->|git add| B(Git Staging Area);
    B -->|git commit| C(Git Repository);
    C -->|git push| D(Git Remote Repository);
    A -->|git status| E(Git Status);

```

