<h1 align="center">💻 GitHub Terminal Stats ⌨️</h1>

<p align="center">
  <img src="https://img.shields.io/github/stars/ChinmayKaitade/GitHub-Terminal-Stats?style=for-the-badge&color=yellow" />
  <img src="https://img.shields.io/github/forks/ChinmayKaitade/GitHub-Terminal-Stats?style=for-the-badge&color=blue" />
  <img src="https://img.shields.io/github/issues/ChinmayKaitade/GitHub-Terminal-Stats?style=for-the-badge&color=orange" />
</p>

<p align="center">
  ⚡ A cool terminal-style GitHub profile stats generator built using GitHub Actions and Node.js!  
</p>

<p align="center">
  <img src="github_stats.svg" alt="GitHub Terminal Stats Preview" />
</p>

---

## 🚀 Features

- 📊 Displays terminal-style GitHub stats
- 🕒 Auto-updates every day using GitHub Actions
- 🧑‍💻 Fully customizable & lightweight
- 🌐 No server or backend required

---

## 📦 Installation & Setup

Follow these simple steps to set up **GitHub Terminal Stats** on your own profile:

### 1️⃣ Fork This Repo

Click the `⭐ Star` and then `🍴 Fork` this repository to your GitHub account.

## 🛠 Usage

1️⃣ **Create a new repository** using this template → [Click Here 🚀](https://github.com/yogeshwaran01/github-stats-terminal-style/generate)  
2️⃣ **Generate a Personal Access Token (PAT)** → [How-to Guide 🔑](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token)  
3️⃣ **Add a Repository Secret** named `GHT` with your PAT → [Guide 🔐](https://docs.github.com/en/actions/reference/encrypted-secrets)  
4️⃣ **Enable** ✅ `Allow GitHub Actions to create and approve pull requests` in **General Action Settings**

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

### 🏃 Running Workflows

#### ▶ Manual Execution

1️⃣ Go to the **Actions** tab  
2️⃣ Select the `main.yml` workflow  
3️⃣ Click **Run Workflow** 🖱

#### ⏱ Automated Execution

- Runs **daily at 2:47 UTC** 🕑
- Change schedule in `/.github/workflows/main.yml` → Use [Cron Generator ⏳](https://crontab.guru/)

---

</details>

---

### 🖼️ Add SVG to Your Profile README

Add the following Markdown to your profile `README.md`:

```md
![GitHub Terminal Stats](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats/github_stats.svg)
```

> Tip: Replace `ChinmayKaitade` with your GitHub username if needed.

---

## 🎨 Themes Available

You can choose from a variety of themes to style your terminal stats:

| Theme Name    | Preview                                                                                                                        |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| `ubuntu`      | ![Ubuntu](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/ubuntu.svg)            |
| `hacker`      | ![Hacker](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/hacker.svg)            |
| `atom`        | ![Atom](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/atom.svg)                |
| `googledark`  | ![Google Dark](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/googledark.svg)   |
| `default`     | ![Default](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/default.svg)          |
| `googlelight` | ![Google Light](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/googlelight.svg) |
| `dracula`     | ![Dracula](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/dracula.svg)          |
| `monokai`     | ![Monokai](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/monokai.svg)          |
| `github`      | ![GitHub](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/github.svg)            |
| `powershell`  | ![Powershell](https://raw.githubusercontent.com/ChinmayKaitade/GitHub-Terminal-Stats-Template/master/themes/powershell.svg)    |

> 📝 You can preview more by editing the `config.js` file and setting different theme names.

---

## 🙌 Contributing

Want to make this even cooler?
Feel free to submit issues or pull requests. Suggestions and improvements are always welcome!

```bash
git clone https://github.com/ChinmayKaitade/GitHub-Terminal-Stats.git
cd GitHub-Terminal-Stats
npm install
npm run dev
```

---

## ☕ Support & Sponsor

If you like this project and want to support its development:

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

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

> Made with ❤️ by Chinmay Kaitade
