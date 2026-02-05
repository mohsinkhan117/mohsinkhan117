# Hi there <img src="https://user-images.githubusercontent.com/30992818/109906379-5aeb8a80-7cdb-11eb-821f-5b7192e8a051.gif" alt="Hi" width="24"/> 
## Flutter Mobile Developer | Cross-Platform Specialist

I'm **M Mohsin Khan**, a passionate Flutter developer specializing in building high-performance, scalable mobile applications for Android and iOS. With expertise in full-stack mobile development, I create seamless user experiences backed by robust backend integration.

<img align="right" height="150" src="https://i.pinimg.com/originals/70/37/d4/7037d478852af21357f038fac2d2e9f6.gif"  />

---

## 🐍 GitHub Contributions Snake

![GitHub Snake Light](https://raw.githubusercontent.com/mohsinkhan117/mohsinkhan117/output/github-contribution-grid-snake.svg#gh-light-mode-only)
![GitHub Snake Dark](https://raw.githubusercontent.com/mohsinkhan117/mohsinkhan117/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only)



---

## 🛠️ Technical Stack

### **Core Expertise**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=white)

### **Backend & Databases**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=FF9900)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

### **Development Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=mohsinkhan117&show_icons=true&theme=radical&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohsinkhan117&layout=compact&langs_count=8&theme=radical" alt="Top Languages" />
</div>

<div align="center">
  <img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=mohsinkhan117&theme=radical" alt="GitHub Streak" />
</div>



---

## 🌟 Professional Focus

- 🔭 **Currently:** Developing enterprise-grade mobile applications using Flutter
- 💡 **Specialized in:** Cross-platform development, API integration, and performance optimization
- 🚀 **Passionate about:** Clean architecture, state management, and scalable app development
- 📱 **Expertise:** Full mobile development lifecycle from concept to deployment

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhsin-archon/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohsinkhanmandan@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=923315265967&text=Hi%2C%20Mohsin%20Khan)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/32317822/mohsin-khan)

---

## 🔧 Setup Instructions for Snake Animation

To add the snake animation to your profile, you need to:

1. **Create a `.github/workflows/snake.yml` file** in your repository with this content:
```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
