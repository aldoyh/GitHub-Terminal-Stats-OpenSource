<h1 align="center">💻 إحصائيات GitHub بتصميم الطرفية - مشروع مفتوح المصدر ⌨️</h1>

<p align="center">
  <img src="https://img.shields.io/github/stars/ChinmayKaitade/GitHub-Terminal-Stats?style=for-the-badge&color=yellow" />
  <img src="https://img.shields.io/github/forks/ChinmayKaitade/GitHub-Terminal-Stats?style=for-the-badge&color=blue" />
  <img src="https://img.shields.io/github/issues/ChinmayKaitade/GitHub-Terminal-Stats?style=for-the-badge&color=orange" />
</p>

<p align="center">
  ⚡ مولد إحصائيات ملف GitHub الشخصي بأسلوب الطرفية الرائع باستخدام GitHub Actions و Node.js!  
</p>

<p align="center">
  <img src="github_stats.svg" alt="معاينة إحصائيات GitHub بتصميم الطرفية" />
</p>

---

## 🚀 المميزات

- 📊 يعرض إحصائيات GitHub بنمط الطرفية
- 🕒 يحدث تلقائياً كل يوم باستخدام GitHub Actions
- 🧑‍💻 قابل للتخصيص بالكامل وخفيف الوزن
- 🌐 لا يتطلب خادم أو خلفية

---

## 📦 التثبيت والإعداد

اتبع هذه الخطوات البسيطة لإعداد **إحصائيات GitHub بتصميم الطرفية** في ملفك الشخصي:

### 1️⃣ عمل نسخة من هذا المستودع

اضغط على `⭐ Star` ثم `🍴 Fork` لعمل نسخة من هذا المستودع إلى حسابك على GitHub.

## 🛠 الاستخدام

1️⃣ **إنشاء مستودع جديد** باستخدام هذا القالب → [اضغط هنا 🚀](https://github.com/yogeshwaran01/github-stats-terminal-style/generate)  
2️⃣ **إنشاء رمز وصول شخصي (PAT)** → [دليل التعليمات 🔑](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token)  
3️⃣ **إضافة سر المستودع** بإسم `GHT` مع رمز PAT الخاص بك → [الدليل 🔐](https://docs.github.com/en/actions/reference/encrypted-secrets)  
4️⃣ **تمكين** ✅ `السماح لـ GitHub Actions بإنشاء وقبول طلبات السحب` في **إعدادات العمل العامة**

---

<details>
  <summary><b>📜 More Setup Details (Click to Expand)</b></summary>
  <br/>

### 🔑 Authentication & Permissions

To allow **GitHub Actions** to commit and push changes automatically:

---

#### 🛠 Setting Up Personal Access Token (PAT)

1️⃣ Navigate to **⚙ Settings → Developer settings → Personal access tokens**  
2️⃣ Click **Generate a new token (classic)**  
3️⃣ Select the following scopes:

- ✅ `repo` → Full control of repositories
- ✅ `workflow` → Trigger & run GitHub Actions

⚠ **Important:** Copy your token now — you won’t be able to see it again!

---

#### 🔐 Adding the Token as a Secret

1️⃣ Go to **Settings → Secrets and Variables → Actions**  
2️⃣ Click **New Repository Secret**  
3️⃣ **Name:** `GHT`  
4️⃣ **Value:** Your copied PAT  
5️⃣ Save ✅

💡 **Security Tip:** Never share your PAT publicly — it can modify your repositories.

---

#### ⚙ Grant Workflow Permissions

1️⃣ Go to **Settings → Actions → General**  
2️⃣ Scroll to **Workflow Permissions**  
3️⃣ Select **Read and write permissions**  
4️⃣ Enable **Allow GitHub Actions to create and approve pull requests**  
5️⃣ Save ✅

---

### 🏃 تشغيل سير العمل

#### ▶ التنفيذ اليدوي

1️⃣ اذهب إلى تبويب **Actions**  
2️⃣ اختر سير عمل `main.yml`  
3️⃣ اضغط على **Run Workflow** 🖱

#### ⏱ التنفيذ التلقائي

- يعمل **يومياً في الساعة 2:47 UTC** 🕑
- غير الجدولة في `/.github/workflows/main.yml` ← استخدم [مولد Cron ⏳](https://crontab.guru/)

---

</details>

---

### 🖼️ إضافة SVG إلى ملف README الشخصي

أضف Markdown التالي إلى ملف `README.md` الشخصي:

```md
![GitHub Terminal Stats](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/github_stats.svg)
```

> نصيحة: استبدل `ChinmayKaitade` باسم المستخدم الخاص بك على GitHub إذا لزم الأمر.

---

## 🎨 القوالب المتاحة

يمكنك اختيار من مجموعة متنوعة من القوالب لتخصيص إحصائياتك بشكل الطرفية:

<table>
  <tr>
    <td align="center" width="50%">
      <strong>ubuntu</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/ubuntu.svg" alt="ubuntu theme preview" />
    </td>
    <td align="center" width="50%">
      <strong>hacker</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/hacker.svg" alt="hacker theme preview" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>atom</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/atom.svg" alt="atom theme preview" />
    </td>
    <td align="center">
      <strong>googledark</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/googledark.svg" alt="googledark theme preview" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>default</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/default.svg" alt="default theme preview" />
    </td>
    <td align="center">
      <strong>googlelight</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/googlelight.svg" alt="googlelight theme preview" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>dracula</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/dracula.svg" alt="dracula theme preview" />
    </td>
    <td align="center">
      <strong>monokai</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/monokai.svg" alt="monokai theme preview" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>github</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/github.svg" alt="github theme preview" />
    </td>
    <td align="center">
      <strong>powershell</strong><br/>
      <img src="https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-OpenSource/master/themes/powershell.svg" alt="powershell theme preview" />
    </td>
  </tr>
</table>

<p align="center">
  🚀 <b>More themes coming soon!</b>  
  ⭐ Star and 🍴 Fork this repo to get the latest updates instantly.
</p>

> 📝 You can preview more by editing the `config.js` file and setting different theme names.

---

## 🙌 المساهمة

تريد جعل هذا أكثر روعة؟  
لا تتردد في تقديم القضايا أو طلبات السحب. الاقتراحات والتحسينات مرحب بها دائماً!

```bash
git clone https://github.com/ChinmayKaitade/GitHub-Terminal-Stats.git
cd GitHub-Terminal-Stats
npm install
npm run dev
```

---

## ☕ الدعم والرعاية

إذا أعجبك هذا المشروع وتريد دعم تطويره:

[![Sponsor](https://img.shields.io/badge/Sponsor%20Project-💖-red?style=for-the-badge)](https://github.com/sponsors/ChinmayKaitade)

---

## 🔗 Let’s Connect

<p align="center">
  <a href="https://www.linkedin.com/in/chinmay-sharad-kaitade" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:chinmaykaitade123@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://twitter.com/chinmaydotcom" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="https://github.com/ChinmayKaitade" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://chinmaykaitadeportfolio.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-58A6FF?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.youtube.com/@chinmaykaitade" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
</p>

---

## 📄 الترخيص

هذا المشروع مرخص تحت [ترخيص MIT](./LICENSE).

---

> صُنع بـ ❤️ بواسطة Chinmay Kaitade
