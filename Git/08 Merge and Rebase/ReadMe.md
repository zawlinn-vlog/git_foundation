> I'm Zaw Linn Tun a Frontend Web Developer on [Zaw Linn Tun](https://www.facebook.com/zawlinn.profile). :heart:

<br>

## Languages &mdash;

<!-- ![Screenshot of Project](./s1.png) -->

What I use packages are &mdash;

[![My Skills](https://skillicons.dev/icons?i=git,github,gitlab,vscode&perline=4)](https://skillicons.dev)

<br>

### Git Merge &mdash;

```sh
    git init
    vim file1.txt # this is the first comment
    vim file2.txt # this is the first comment
    git add .
    git commit -m "File1 and file2 are added"

    git checkout -b new-feature
    git branch
    vim file3.txt # this is the first comment
    vim file4.txt # this is the first comment
    git add .
    git commit -m "File3 and file4 are added"

    git checkout main/master
    git merge new-feature
    git branch
    git log --oneline
    ls
```

```
    A
     \
      B - C
```

```sh
    git merge feature
```

```
    A - B - C
```

### Rebase vs Merge

Main/Master ကိုတည်ဆောက်မယ်

```sh
    git init
    git branch -M main
    vim file1.txt # comment text
    git add .
    git commit -m "F1"

    git checkout -b feature

    git branch feature
    git chekcout feature

    vim file2.txt # comment text
    git add .
    git commit -m "F2"

    vim file3.txt # comment text
    git add .
    git commit -m "F3"

    git checkout main/master
    vim file4.txt # comment text
    git add .
    git commit -m "F4"
```

```
    A - - - - - - D
     \
      B - C
```

```sh
    git merge feature
```

```
    A - D - E(M)
     \     /
      B - C
```

> E(M) is New Commit

### Rebase

```
    A - - - - - - D
     \
      B - C
```

```sh
    git checkout feature
    git rebase main

    git checkout main
    git merge feature
```

```
    A - D - B - C
```

<!-- TODO: Add last video link -->

📫 Reach me out!

[![Gamil Badge](https://img.shields.io/badge/-Gmail-c0392b?style=flat&labelColor=c0392b&logo=gmail&logoColor=white)](mailto:zawlinn.profile@gmail.com)

<details>
    <summary>
        My Portfolio
    </summary>
    <br/>

- :earth_asia: I’m currently working at @Mae Sot Market as a sale staff
- :computer: Most used line of code git commit -m "Initial Commit"
- :brain: I’m looking for help with Outstanding Video ideas.
- :mailbox_with_mail: How to reach me: zawlinn.profile@gmail.com.
- :heart: In a relationship with React
</details>
