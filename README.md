# 👋 Hey there! I'm antonio

💻 Senior Software Engineer | 🕵️‍♂️ Web Crawling Enthusiast | 🇧🇷 Brazilian

## 🚀 About Me

I'm a passionate senior software engineer specializing in **PHP**, **Node**, **Go** and **Python** with a strong interest in **web scraping & automation**. I love diving into data, building efficient APIs, and creating tools that make the web more accessible.

In my spare time I work on a side project called [ilovediscount.com](https://ilovediscount.com) that aims to democratize online shopping deals worldwide. The platform monitors major e-commerce websites, rapidly compiling their complete product catalogs and tracking price changes in real-time. This enables users to discover the best discounts available across global marketplaces.

## 🛠️ Tech Stack

- 🐘 **PHP** (Laravel, Symfony, Yii2)
- 🐍 **Python** (FastAPI, Django, Pandas, BeautifulSoup)
- ⚡ **Node.js** (Fastify, Prisma, Next.js, BullMQ, Zod, Winston, React, React Native)
- 🦫 **Golang** (Gin, GORM, Testify)
- 🕸️ **Web Scraping** (Puppeteer, Playwright, Got, Cheerio)
- 🗄️ **Databases** (MySQL, PostgreSQL, Redis, DynamoDB, MongoDB, Valkey, ClickHouse)
- ☁️ **DevOps** (Docker, Nginx, AWS, GCP, Coolify)

## 🌱 What I'm Learning

- Advanced **AI & ML for Web Scraping**
- **Distributed Systems** and Microservices

## 📫 Let's Connect!

- 🔗 [LinkedIn](https://www.linkedin.com/in/acgfbr)
- 🐦 [Twitter/X](https://x.com/acgfbr)

🚀 **"Best price monitoring tool, come on, [ilovediscount.com](https://ilovediscount.com)"**

## 🚀 Tech Stack of iLoveDiscount

The **backend** is built with **Laravel 11**, while the **frontend** uses **React** and **Tailwind CSS**.

### ⚡ Backend & Architecture

- **Laravel Octane** with **FrankenPHP** serves as the HTTP entry point (**no Nginx needed! 🚀**).
- **InertiaJS with SSR** connects the frontend and backend seamlessly, making it a **small yet efficient monolith**.
- **Laravel Horizon + Redis** handles fast queue jobs (e.g., email notifications, password resets).
- **RabbitMQ** processes analytics and extension history.
- **MySQL 8** serves as the main database, while **ClickHouse** powers analytics.
- **ElasticSearch (WIP)** is being integrated for **hybrid search**.
- **Custom i18n system**: A lightweight JSON-based translation system built in-house.
- **WebSockets (Laravel Reverb)** delivers real-time notifications.

### 🕸️ Web Scraping & Crawlers

- The main **web crawler** is built with **Playwright**, utilizing **rotating proxies** via [Scrapoxy.io](https://scrapoxy.io) on **spot cloud machines** for dynamic IP rotation.

### 🌍 Browser Extension

- Built with **extension.js.org**, **React**, and **pure CSS**.

### 🪻 Microservices

- A **small Go microservice** manages notifications and extension history. It enqueues messages into **RabbitMQ** for background processing by Laravel.

### ☁️ Deployment & Infrastructure

- Everything is **Dockerized** and orchestrated using **Coolify**.
- Running on a **Contabo VPS** with **24 vCPUs** and **120GB RAM**.

![asap](asap_as_possible.png)
