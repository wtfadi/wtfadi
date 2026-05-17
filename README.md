<style>
  @keyframes wave {
    0%, 100% { transform: rotate(0deg); }
    25% { transform: rotate(20deg); }
    75% { transform: rotate(-20deg); }
  }
  @keyframes glow {
    0%, 100% { text-shadow: 0 0 10px rgba(88, 166, 255, 0.5); }
    50% { text-shadow: 0 0 20px rgba(88, 166, 255, 0.8), 0 0 30px rgba(88, 166, 255, 0.6); }
  }
  @keyframes slideDown {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  @keyframes pulse {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.6; }
  }
  @keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
  }
  .animated-title {
    animation: glow 2s ease-in-out infinite, slideDown 0.8s ease-out;
  }
  .wave-emoji {
    animation: wave 1s ease-in-out infinite;
    display: inline-block;
  }
  .subtitle-animation {
    animation: slideDown 1s ease-out;
  }
</style>

<div align="center">

# <span class="animated-title"><span class="wave-emoji">👋</span> Hi, I'm Aditya Raj</span>

### <span class="subtitle-animation">🚀 DevOps Engineer | 🛡️ Cybersecurity Enthusiast | ⚡ Automation Developer</span>

<div style="margin: 20px 0; animation: float 3s ease-in-out infinite;">

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white&labelColor=1a1a1a)](https://www.instagram.com/xpz_xz)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a1a)](mailto:aditya6974yt@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/wtfadi?style=for-the-badge&logo=github&labelColor=1a1a1a)](https://github.com/wtfadi)

</div>

</div>

<style>
  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  .animated-divider {
    height: 3px;
    background: linear-gradient(90deg, #58A6FF, #1F6FEB, #58A6FF);
    background-size: 200% 100%;
    animation: gradientShift 3s ease infinite;
    margin: 30px 0;
  }
  .about-section {
    animation: slideDown 1.2s ease-out;
  }
</style>

<div class="animated-divider"></div>

## 🚀 About Me

<div class="about-section">

I'm a DevOps enthusiast and cybersecurity student passionate about building intelligent automation solutions. Currently pursuing advanced skills in cloud infrastructure, security automation, and IoT development. I love turning complex problems into elegant, automated solutions.

</div>

<style>
  @keyframes codeGlow {
    0%, 100% { box-shadow: 0 0 10px rgba(88, 166, 255, 0.3); }
    50% { box-shadow: 0 0 20px rgba(88, 166, 255, 0.6), inset 0 0 10px rgba(88, 166, 255, 0.2); }
  }
  .code-block {
    animation: codeGlow 3s ease-in-out infinite;
    border-left: 4px solid #58A6FF;
    border-radius: 8px;
  }
</style>

<div class="code-block">

```python
class Developer:
    def __init__(self):
        self.name = "Aditya Raj"
        self.role = "DevOps & Security Engineer"
        self.interests = ["Cybersecurity", "Automation", "Cloud Computing", "IoT"]
        self.learning = ["Kubernetes", "Cloud Security", "Penetration Testing"]
        self.motto = "Break it → Fix it → Automate it"
    
    def say_hi(self):
        print("Thanks for stopping by! Let's build something awesome together.")

me = Developer()
me.say_hi()
```

</div>

- 🔐 Passionate about **Cybersecurity** & **Ethical Automation**
- 🤖 Building intelligent **Bots, Scripts & Automation Tools**
- ☁️ Exploring **DevOps stacks** (Docker, Kubernetes, CI/CD, Cloud)
- 🎯 Currently focusing on **Cloud Security** & **Infrastructure Automation**
- ⚡ Always learning, always building

---

## 🛠️ Tech Stack

<style>
  @keyframes badgePulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.05); }
  }
  .badge-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    animation: slideDown 1.4s ease-out;
  }
  .badge-item {
    animation: badgePulse 2s ease-in-out infinite;
    transition: all 0.3s ease;
  }
  .badge-item:hover {
    filter: brightness(1.3) drop-shadow(0 0 8px rgba(88, 166, 255, 0.8));
  }
</style>

### Languages & Scripting
<div class="badge-container">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

</div>

### DevOps & Cloud
<div class="badge-container">

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

### Security & Tools
<div class="badge-container">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=nmap&logoColor=white)

</div>

---

## 🏆 Certifications & Achievements

<style>
  @keyframes tableSlideIn {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  .cert-table {
    animation: tableSlideIn 1.6s ease-out;
    display: inline-block;
  }
  .cert-emoji {
    animation: float 3s ease-in-out infinite;
    display: inline-block;
  }
</style>

<div align="center">

<div class="cert-table">

| <span class="cert-emoji">🏅</span> Certification | Issuer | Date | Skills |
|---|---|---|---|
| <span class="cert-emoji">🐳</span> **Docker Foundations** | LinkedIn Learning | Oct 2025 | Containerization, Docker Products |
| <span class="cert-emoji">🛡️</span> **Cybersecurity Analyst** | Forage (Deloitte) | Nov 2025 | IAM, Security Strategy, Access Control |
| <span class="cert-emoji">🔒</span> **Shields Up Cybersecurity** | Forage | Nov 2025 | Zero-day Vulnerabilities, Ransomware Defense |
| <span class="cert-emoji">💻</span> **IT Service Management** | LinkedIn Learning | Oct 2025 | IT Service Desk, Service Management |
| <span class="cert-emoji">📚</span> **Docker: Your First Project** | LinkedIn Learning | Oct 2025 | Docker Containerization & Deployment |

</div>

</div>

---

## 📊 GitHub Statistics

<style>
  @keyframes statsZoom {
    from {
      opacity: 0;
      transform: scale(0.95);
    }
    to {
      opacity: 1;
      transform: scale(1);
    }
  }
  .stats-container {
    animation: statsZoom 1.8s ease-out;
  }
  .stat-item {
    margin: 15px 0;
    animation: slideDown 2s ease-out;
  }
</style>

<div align="center">
  
<div class="stats-container">

<div class="stat-item">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=wtfadi&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9&cache_id=2025)

</div>

<div class="stat-item">

![GitHub Streak](https://streak-stats.demolab.com/?user=wtfadi&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=FF6B6B&currStreakLabel=C9D1D9&cache_id=2025)

</div>

<div class="stat-item">

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wtfadi&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&cache_id=2025)

</div>

</div>

</div>

---

## 🏅 Featured Projects

<style>
  @keyframes projectHover {
    0%, 100% { transform: translateY(0) rotateZ(0deg); }
    50% { transform: translateY(-8px) rotateZ(1deg); }
  }
  .projects-container {
    animation: slideDown 2.2s ease-out;
  }
  .project-card {
    animation: projectHover 3s ease-in-out infinite;
    transition: filter 0.3s ease;
  }
  .project-card:hover {
    filter: brightness(1.1) drop-shadow(0 0 15px rgba(88, 166, 255, 0.8));
  }
</style>

<div align="center">

<div class="projects-container">

<div class="project-card">

[![B.Tech Exam Prep AI](https://github-readme-stats.vercel.app/api/pin/?username=wtfadi&repo=B.Tech-Exam-prep-AI&theme=tokyonight&hide_border=true&bg_color=0D1117)](https://github.com/wtfadi/B.Tech-Exam-prep-AI)

</div>

<div class="project-card">

[![Test Chatbot](https://github-readme-stats.vercel.app/api/pin/?username=wtfadi&repo=Test-chatbot&theme=tokyonight&hide_border=true&bg_color=0D1117)](https://github.com/wtfadi/Test-chatbot)

</div>

</div>

</div>

---

## 🎯 Current Focus

<style>
  @keyframes focusGlow {
    0%, 100% { border-color: rgba(88, 166, 255, 0.3); box-shadow: 0 0 10px rgba(88, 166, 255, 0.2); }
    50% { border-color: rgba(88, 166, 255, 0.8); box-shadow: 0 0 20px rgba(88, 166, 255, 0.5), inset 0 0 10px rgba(88, 166, 255, 0.1); }
  }
  .focus-code {
    animation: focusGlow 2.5s ease-in-out infinite, slideDown 2.4s ease-out;
    border: 2px solid rgba(88, 166, 255, 0.3);
    border-radius: 8px;
    padding: 15px;
  }
</style>

<div class="focus-code">

```yaml
learning:
  - Advanced Kubernetes orchestration & cluster management
  - Cloud security best practices (AWS, Azure)
  - Penetration testing methodologies
  - DevSecOps practices
  
building:
  - Automated CI/CD deployment pipelines
  - Security automation tools & scripts
  - Smart IoT applications
  - Intelligent chatbots and assistants
  
exploring:
  - Bug bounty programs & vulnerability disclosure
  - Open source contributions
  - CTF challenges & security research
  - Advanced containerization patterns
```

</div>

---

## 💡 Fun Fact

<style>
  @keyframes quoteSlide {
    0% { opacity: 0; transform: translateX(-20px); }
    100% { opacity: 1; transform: translateX(0); }
  }
  .fun-fact-box {
    animation: quoteSlide 2.6s ease-out;
    border-left: 5px solid;
    border-image: linear-gradient(to bottom, #58A6FF, #1F6FEB, #58A6FF) 1;
    padding: 15px 20px;
    background: rgba(88, 166, 255, 0.05);
    border-radius: 5px;
  }
</style>

<div class="fun-fact-box">

> "I don't just write code — I automate everything, one script at a time! ⚡"
> 
> *Because manual work is just code that hasn't been automated yet.*

</div>

---

<div align="center">

<style>
  @keyframes buttonShine {
    0%, 100% { background-position: 200% center; }
    50% { background-position: 0% center; }
  }
  @keyframes connectSlide {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .connect-section {
    animation: connectSlide 2.8s ease-out;
  }
  .connect-badge {
    animation: badgePulse 2.5s ease-in-out infinite;
    transition: all 0.3s ease;
  }
  .connect-badge:hover {
    filter: brightness(1.4) drop-shadow(0 0 12px rgba(88, 166, 255, 0.9));
    transform: scale(1.1);
  }
</style>

### 🤝 Let's Connect

<div class="connect-section">

I'm always open to collaborating on interesting projects, discussing technology, or exploring new opportunities in DevOps and cybersecurity!

<div style="margin: 20px 0;">

<span class="connect-badge">

[![Follow GitHub](https://img.shields.io/badge/Follow-wtfadi-181717?style=for-the-badge&logo=github&labelColor=000000)](https://github.com/wtfadi)

</span>

<span class="connect-badge">

[![Connect Instagram](https://img.shields.io/badge/Connect-%40xpz__xz-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=1a1a1a)](https://www.instagram.com/xpz_xz)

</span>

<span class="connect-badge">

[![Email Me](https://img.shields.io/badge/Email-aditya6974yt@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a1a)](mailto:aditya6974yt@gmail.com)

</span>

</div>

</div>

<div class="animated-divider" style="margin-top: 30px;"></div>

<style>
  @keyframes starGlow {
    0%, 100% { filter: drop-shadow(0 0 2px rgba(255, 215, 0, 0.5)); }
    50% { filter: drop-shadow(0 0 8px rgba(255, 215, 0, 0.9)); }
  }
  .footer-text {
    animation: connectSlide 3s ease-out;
  }
  .star-emoji {
    animation: starGlow 1.5s ease-in-out infinite;
    display: inline-block;
  }
</style>

<div class="footer-text">

<span class="star-emoji">⭐</span> **From [wtfadi](https://github.com/wtfadi)** — *Building the future, one commit at a time* <span class="star-emoji">⭐</span>

</div>

</div>

</div>
