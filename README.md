<div align="center">

# 💻 API-First Developer Resume
**A serverless, terminal-native resume for Cloud & DevOps engineers.**

![JSON](https://img.shields.io/badge/Format-JSON-lightgrey?style=for-the-badge&logo=json)
![Hosting](https://img.shields.io/badge/Hosting-GitHub_Pages-181717?style=for-the-badge&logo=github)
![Architecture](https://img.shields.io/badge/Architecture-Serverless-FF9900?style=for-the-badge&logo=aws)
![Terminal](https://img.shields.io/badge/Access-cURL-4D4D4D?style=for-the-badge&logo=gnu-bash)

</div>

---

## 📖 Overview
Why send a static PDF when you can serve structured data? This repository acts as a serverless API endpoint that delivers my latest skills, education, and infrastructure projects as raw JSON data. 

It is designed for recruiters and senior engineers who prefer to stay in the command line.

##🏗️ The Architecture

This project demonstrates an understanding of stateless data delivery and GitOps principles:
The Database: A flat resume.json file acting as the single source of truth.

The CDN: Hosted entirely on GitHub Pages, providing a fast, serverless, and globally distributed endpoint without the need for traditional backend routing.

The Updates: Updating my resume is as simple as pushing a new git commit. No servers to manage.

👨‍💻 About the Author

Patel Piyush Aspiring DevOps Engineer & Cloud Computing Student

I build enterprise-grade CI/CD pipelines, automated incident response systems, and serverless architectures.

🔗 GitHub: @maiiapiyushhoon

💼 LinkedIn: Patel Piyush

## 🚀 How to Fetch
You don't need to download a file. Open your Linux, Mac, or Windows (WSL) terminal and run the following command to `GET` my resume directly via the web:

```bash
curl [https://maiiapiyushhoon.github.io/resume-api/resume.json](https://maiiapiyushhoon.github.io/resume-api/resume.json)


