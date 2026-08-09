> I'm Zqw Linn Tun a Frontend Web Developer on [Zqw Linn Tun](https://www.facebook.com/zawlinn.profile). :heart:

<br>

## Languages &mdash;

<!-- ![Screenshot of Project](./s1.png) -->

What I use packages are &mdash;

[![My Skills](https://skillicons.dev/icons?i=git,github,gitlab,vscode&perline=4)](https://skillicons.dev)

<br>

### Git Commit &mdash;

အတိုချုပ်ပြောရရင် **နှစ်ခုလုံး Remote Repository က data တွေကို Local Repository ဆီကို ယူပေးပါတယ်။** ဒါပေမယ့် **လုပ်ပုံလုပ်နည်းက မတူပါဘူး။**

### `git fetch`

Remote က commit, branch, tag အသစ်တွေကို **Local Repository ထဲကိုသာ ဒေါင်းလုပ်လုပ်ပေးတယ်**။

✅ Working Directory ကို **မပြောင်းဘူး**
✅ Local Branch ကို **မပြောင်းဘူး**
✅ Remote Tracking Branch (`origin/main`, `origin/dev`) ကိုပဲ update လုပ်ပေးတယ်။

```
Remote
   │
   ▼
Local Repo (origin/main)   ✅ Update
Local main                 ❌ No change
Working Files              ❌ No change
```

ဥပမာ

```bash
git fetch origin
```

ပြီးရင်

```bash
git log --oneline --all --graph
```

ကြည့်လိုက်ရင် `origin/main` က ရှေ့ကိုတက်သွားပြီး `main` က မတက်သေးတာကို တွေ့ရမယ်။

---

### `git pull`

`pull` က

1. `fetch`
2. `merge` (သို့) `rebase`

ကို **တစ်ခါတည်းလုပ်ပေးတာ** ဖြစ်ပါတယ်။

```
git pull origin main
```

အတွင်းမှာ

```
git fetch origin
git merge origin/main
```

လုပ်တာနဲ့တူပါတယ်။

ဒါကြောင့်

```
Remote
   │
   ▼
Local Repo (origin/main)   ✅ Update
        │
        ▼
Local main                 ✅ Update
Working Files              ✅ Update
```

---

## ဘယ်အချိန်မှာ ဘယ်ဟာသုံးမလဲ

### ✅ fetch

Remote မှာ ဘာတွေပြောင်းထားလဲ အရင်ကြည့်ချင်ရင်

```bash
git fetch origin
git log HEAD..origin/main --oneline
```

ဒါမှမဟုတ်

```bash
git diff main origin/main
```

ပြီးမှ Merge/Rebase လုပ်နိုင်တယ်။

Professional Team တွေက ဒီနည်းကို ပိုသုံးကြတယ်။

---

### ✅ pull

Remote က update တွေကို **ချက်ချင်းယူပြီး Local Branch ထဲထည့်ချင်ရင်**

```bash
git pull
```

တစ်ကြောင်းတည်းနဲ့ပြီးတယ်။

---

## Team Workflow

အများဆုံးတွေ့ရတဲ့ Workflow က

```bash
git fetch origin
git status
git log HEAD..origin/main --oneline
git rebase origin/main
```

ဒါမှမဟုတ်

```bash
git fetch origin
git merge origin/main
```

`pull` ထက် `fetch` ကို အရင်လုပ်ပြီး စစ်ဆေးတာက conflict ဖြစ်နိုင်ခြေ၊ မမျှော်လင့်တဲ့ merge commit ဖြစ်နိုင်ခြေကို ပိုကောင်းစွာ ထိန်းချုပ်နိုင်ပါတယ်။

---

## အကျဉ်းချုပ်

| Command     | Remote မှ ဒေါင်းမလား | Local Branch Update | Working Directory Update |
| ----------- | -------------------- | ------------------- | ------------------------ |
| `git fetch` | ✅ Yes               | ❌ No               | ❌ No                    |
| `git pull`  | ✅ Yes               | ✅ Yes              | ✅ Yes                   |

**မှတ်ရန်**

- **ဒေါင်းယူချင်ရုံ** ⇒ `git fetch`
- **ဒေါင်းယူပြီး ကိုယ့် branch ကိုပါ update လုပ်ချင်** ⇒ `git pull`

<!-- TODO: Add last video link -->

📫 Reach me out!

[![Gamil Badge](https://img.shields.io/badge/-Gmail-c0392b?style=flat&labelColor=c0392b&logo=gmail&logoColor=white)](mailto:zalwinn.profile@gmail.com)

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
