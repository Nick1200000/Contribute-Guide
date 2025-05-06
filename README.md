🌟 Beginner-Friendly GitHub Contribution Guide (Hindi-English)
==============================================================

Yeh guide tumhare jaise naye contributors ke liye hai jo kisi open source project me pehli baar contribution kar rahe hain.

* * * * *

🧩 Step-by-Step Process to Contribute
-------------------------------------

### ✅ 1. **GitHub Account banao**

Agar tumhare paas GitHub account nahi hai toh [github.com](https://github.com/) jaake ek account bana lo.

### 🍴 2. **Fork karo original repo**

Jaise hi tumhe koi acha open-source project milta hai:

-   Project ke page pe jaao

-   Top right me `Fork` ka button dikh raha hoga --- uspe click karo

-   Ab tumhare GitHub pe us repo ka ek **copy (fork)** ban jayega

### 📥 3. **Clone karo forked repo**

Terminal ya VSCode open karke command run karo:

```
git clone https://github.com/your-username/first-contributions.git

```

Us folder me jao:

```
cd first-contributions

```

### 🌱 4. **Naya branch banao**

```
git checkout -b add-your-name

```

### 📝 5. **File edit karo (e.g., Contributors.md)**

Apna naam `Contributors.md` file me add karo:

```
- [Your Name](https://github.com/your-github-username)

```

### 💾 6. **Changes save karke commit karo**

```
git add Contributors.md

```

Ya safe method:

```
git add -p

```

```
git commit -m "Add <your-name> to Contributors list"

```

### 🚀 7. **Changes push karo GitHub pe**

```
git push origin add-your-name

```

### 🔁 8. **Pull Request (PR) banao**

-   GitHub pe jaake tumhare branch pe `Compare & pull request` ka button aayega --- uspe click karo

-   Title aur Description fill karo (agar kuch aur improve karna hai toh likh do)

-   Submit PR

### ✅ 9. **PR review ke baad merge hoga**

-   Project ke owner ya maintainer tumhara PR check karega

-   Agar sab sahi hai, toh **merge** ho jayega

-   Toh tumhare changes **original repo me dikhne lagte hain**

* * * * *

⚠️ Common Problems I Faced & Their Solutions
--------------------------------------------

### ❌ Problem: Bar bar GitHub CLI se login maang raha tha

✅ Solution: `gh auth login` command se token use karke login karna pada

### ❌ Problem: File me extra changes ho gaye the

✅ Solution: `git add -p` se **sirf jo changes chahiye wahi add** karo, pura file mat add karo

### ❌ Problem: PR banate time description unclear tha

✅ Solution: Default description ko customize karo, aur checklist complete karo

* * * * *

🔚 Tips
-------

-   `git status` se check karte raho kya changes stage ho rahe hain

-   PR banate waqt achha title aur clear message likho

-   Kabhi bhi `main` branch pe direct kaam mat karo --- hamesha naya branch banao

* * * * *

🚀 You Did It!
--------------

Agar tumne ye steps follow kiye, toh tumhara pehla open-source contribution ho chuka hai! 🔥

Aage kisi bhi project me ye hi steps rahenge --- bas file aur purpose change hoga.

Happy contributing 💻✨
