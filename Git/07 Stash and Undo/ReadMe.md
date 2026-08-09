> I'm Zaw Linn Tun a Frontend Web Developer on [Zaw Linn Tun](https://www.facebook.com/zawlinn.profile). :heart:

<br>

## Languages &mdash;

<!-- ![Screenshot of Project](./s1.png) -->

What I use packages are &mdash;

[![My Skills](https://skillicons.dev/icons?i=git,github,gitlab,vscode&perline=4)](https://skillicons.dev)

<br>

### Git Stash &mdash;

```sh
    git init
    vim file1.txt
    git add .
    git commit -m "Add File 1"

    vim file2.txt
    git add .
    git stash
    git stash list

    vim file3.txt
    git add .
    git stash
    git stash list
    git stash show

    vim file4.txt
    git add .
    git stash
    git stash list
    git stash save "added file 5 6 7"

    git stash pop # pop last of git stash
    git stash apply # if you use apply then you must use git stash pop again

    git stash clear # Delete all stash lists
    git stash drop stash@{0}
    git stash drop stash@{1}

    git stash push --include-untracked
    git stash drop
```

### Undo Change &mdash;

```sh
    vim test01.txt
    git init
    git add * # git add -A / git ad .
    git commit -m "A File is added"
    git status

    touch test02.txt file03.txt

    vim test02.txt

    # This is first line
    # This is second line

    ls # see 3 files

    rm file03.txt # can recover

    git checkout file03.txt # recover code

    git rm file01.txt # cannot recover

```

> checkout လုပ်ရာတွင် staging area ထဲ ထည့်ပီးနောက် recover ပြန်ချင်ရင်

```sh
    rm fileanme.txt
    git add .
    git restore --staged filename.txt
    git checkout filename.txt
```

> အကယ်၍ restore ပြန်လုပ်ချင်ရင် staging area ထဲမရောက်ခင် သို့ ပြန်ထွက်ရပါမယ်။ local repo ထဲ ထည့်လိုက်ရင်တော့ လုံးဝမရတော့ပါ။

```sh
    vim filename.txt # edit
    git restore filename.txt # အရင်အခြေနေကို restore လုပ်ခြင်း
    git add . # if staging area
    git reset filename.txt
    git restore filename.txt

    git log
    git log -3
    git log --oneline
    git log --all --oneline

```

> ဖိုင်တစ်ဖိုင်တည်းကို မိမိလိုချင်သော အခြေအနေကို ပြန်သွားချင်ရင်တော့ checkout ကို အသုံးပြုနိုင်သည်။ သူက staging area အနေအထားကို ရောက်ရှိိနေမှာ ဖြစ်ပါတယ်။

```sh
    git checkout commit_no. -- filename.txt
    git checkout commit_no. filename.txt
```

> အရင်လုပ်ခဲ့တဲ့ ဖိုင်အနေအထား(ဥပမာ - အရင်နှစ်ဖိုင်တည်းအခြေအနေကို ပြန်သွားချင်ရင်တော့)

```sh
    git checkout commit_no.
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
