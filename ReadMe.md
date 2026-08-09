> I'm Zaw Linn Tun a Frontend Web Developer on [Zaw Linn Tun](https://www.facebook.com/zawlinn.profile). :heart:

<br>

## Languages &mdash;

<!-- ![Screenshot of Project](./s1.png) -->

What I use packages are &mdash;

[![My Skills](https://skillicons.dev/icons?i=git,github,gitlab,vscode&perline=4)](https://skillicons.dev)

<br>

## This is foundation Course of Git &mdash;

ဒီ Course မှာ Web Dev တွေ မသိမဖြစ် လိုအပ်တဲ့ Git and Gitlab တွေအကြောင်း လေ့လာရမှာ ဖြစ်ပါတယ်။

Git ကို တစ်ကြောင်းတည်းနဲ့ ပြောရရင်—

> **Git ဆိုတာ Version Control System (VCS) တစ်ခုဖြစ်ပြီး Code တွေရဲ့ ပြောင်းလဲမှုမှတ်တမ်းကို သိမ်းဆည်း၊ စီမံ၊ ပြန်လည်ရယူနိုင်အောင် လုပ်ပေးတဲ့ Tool တစ်ခုပါ။**

Git ကို 2005 ခုနှစ်မှာ **Linus Torvalds** (Linux ကို ဖန်တီးသူ) က Linux Kernel Project အတွက် ဖန်တီးခဲ့ပါတယ်။

---

# Git ကို ဘာကြောင့် အသုံးပြုရတာလဲ

Git မရှိဘဲ Project တစ်ခုလုပ်မယ်ဆိုရင်

```
project/
    index.html

နောက်နေ့

project_new/
    index.html

နောက်တစ်နေ့

project_final/
    index.html

နောက်တစ်နေ့

project_final2/
    index.html

project_final_final/
```

ဒီလို Folder တွေက များလာမယ်။

---

Git သုံးရင်

```
Project
    index.html

Commit 1
Commit 2
Commit 3
Commit 4
Commit 5
```

Folder တစ်ခုတည်းနဲ့

Version အားလုံးကို Git က မှတ်ထားပေးပါတယ်။

---

## Git ရဲ့ အကျိုးကျေးဇူး

### 1. History သိမ်းပေးတယ်

ဥပမာ

```
Commit 1
Navbar

Commit 2
Slider

Commit 3
Login

Commit 4
Dark Mode
```

၃ လကြာပြီး

> Dark Mode က Bug ဖြစ်နေတယ်

ဆိုရင်

Commit 3 ကို ပြန်သွားလို့ရတယ်။

---

### 2. Collaboration

Developer 10 ယောက်

```
main

A → Navbar

B → Footer

C → Login

D → API
```

တစ်ယောက်နဲ့တစ်ယောက် မထိခိုက်ဘဲ အလုပ်လုပ်နိုင်တယ်။

---

### 3. Backup

Laptop ပျက်သွားရင်

GitHub ပေါ်မှာ Code ရှိနေသေးတယ်။

---

### 4. Experiment

Feature အသစ် စမ်းချင်တယ်။

Branch အသစ်ထုတ်

```
main

feature/payment
```

စမ်းပြီး

မကြိုက်ရင် Branch ဖျက်လိုက်ရုံပဲ။

---

### 5. Undo

မှားဖျက်လိုက်တယ်

```
git restore
git checkout
git reflog
git reset
```

တို့နဲ့ ပြန်ယူလို့ရတယ်။

---

# Git အလုပ်လုပ်ပုံ

Git ကို နားလည်ဖို့ ဒီ Diagram ကို အရင်ကြည့်ပါ။

```
Working Directory
        │
        │ git add
        ▼
Staging Area (Index)
        │
        │ git commit
        ▼
Local Repository (.git)
        │
        │ git push
        ▼
Remote Repository (GitHub)
```

ဒီ Pipeline ကို Git ရဲ့ အခြေခံ Workflow လို့ ခေါ်ပါတယ်။

---

## Step 1 — Working Directory

ဒီနေရာက

ကိုယ်အလုပ်လုပ်နေတဲ့ Folder ပါ။

```
project/

index.html

style.css

app.js
```

File ပြင်လိုက်တာနဲ့

Git က

```
Modified
```

လို့ သိနေတယ်။

---

## Step 2 — git add

```
git add app.js
```

ဒါက

> ဒီ File ကို Commit လုပ်ဖို့ အဆင်သင့်ဖြစ်ပြီ

လို့ ပြောတာ။

ဒီအချိန် File က

Staging Area ထဲ ရောက်သွားတယ်။

```
Working

↓

Staging
```

---

## Step 3 — git commit

```
git commit -m "Add login page"
```

Git က

Snapshot တစ်ခု သိမ်းလိုက်တယ်။

```
Commit A

↓

Commit B

↓

Commit C
```

Commit တစ်ခုချင်းစီက Project ရဲ့ အခြေအနေကို ကိုယ်စားပြုတဲ့ Snapshot တစ်ခုပါ။

---

## Step 4 — git push

Local Repository ထဲမှာပဲ ရှိသေးတယ်။

GitHub ကို ပို့ချင်ရင်

```
git push
```

လုပ်ရတယ်။

```
Local

↓

GitHub
```

---

# Git က File ကို ဘယ်လိုသိမ်းတာလဲ

လူအများထင်တာက

```
Commit 1

index.html

Commit 2

index.html

Commit 3

index.html
```

File ကို ထပ်ခါထပ်ခါ Copy ကူးသိမ်းတယ်လို့ ထင်ကြတယ်။

တကယ်တော့ **မဟုတ်ပါဘူး**။

Git က Content ကို SHA-1 Hash နဲ့ Object အဖြစ် သိမ်းထားပြီး တူညီတဲ့ Content ကို ထပ်မသိမ်းဘဲ ပြန်အသုံးပြုပါတယ်။ Commit တစ်ခုစီက အဲဒီ Object တွေကို ညွှန်းထားတဲ့ Metadata နဲ့ Parent Commit ကို သိမ်းထားတာပါ။ ဒါကြောင့် Git က မြန်ပြီး Storage လည်း သက်သာပါတယ်။

---

# Git Repository ထဲမှာ ဘာတွေရှိလဲ

```
.git/

objects/

refs/

HEAD

config

index

logs/
```

ဒီ Folder ထဲမှာ Git ရဲ့ Database အားလုံး ရှိပါတယ်။

---

# Git ရဲ့ အဓိက Components

```
Working Directory

↓

Index (Staging Area)

↓

Repository

↓

Remote
```

---

# Git ကို Database နဲ့ နှိုင်းယှဉ်ကြည့်မယ်

```
Working Directory
        ↓
Temporary Table

↓

Staging Area
        ↓
Save Button

↓

Commit
        ↓
Database Record

↓

Push
        ↓
Cloud Database
```

---

# Git Internals (အတွင်းပိုင်း)

Git အလုပ်လုပ်တာက

```
Blob
Tree
Commit
Tag
```

ဆိုတဲ့ Object လေးမျိုးပေါ် အခြေခံထားပါတယ်။

```
Blob
    ↓

Tree
    ↓

Commit
    ↓

Branch
```

ဒီအပိုင်းကို နားလည်သွားရင် Git ကို ပိုမိုနက်နဲစွာ နားလည်လာပါလိမ့်မယ်။

---

# Git Workflow အပြည့်အစုံ

```
Edit File

↓

git status

↓

git add

↓

git commit

↓

git branch

↓

git merge / git rebase

↓

git push

↓

GitHub

↓

Other Developer

↓

git fetch

↓

git pull
```

---

# အကျဉ်းချုပ်

Git သည်—

- **Version Control** — Code ပြောင်းလဲမှုမှတ်တမ်းကို သိမ်းဆည်းပေးသည်။
- **Collaboration** — Developer အများအပြားကို တစ်ပြိုင်နက် အလုပ်လုပ်နိုင်စေသည်။
- **Backup** — Remote Repository (ဥပမာ GitHub) သို့ Push လုပ်ထားပါက Backup အဖြစ် အသုံးဝင်သည်။
- **Experiment** — Branch များဖြင့် Feature အသစ်များကို လွတ်လပ်စွာ စမ်းသပ်နိုင်သည်။
- **Recovery** — Commit History နှင့် Git Tools များကို အသုံးပြု၍ အမှားများကို ပြန်လည်ရယူနိုင်သည်။

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
