<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,100:0ea5e9&height=200&section=header&text=Hi%20%F0%9F%91%8B%2C%20I%27m%20Dhruv&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20Developer%20%C2%B7%20Backend%20%C2%B7%20PostgreSQL%20%C2%B7%20Web%20Security%20%C2%B7%20Mumbai%2C%20IN&descAlignY=58&descSize=18" alt="Header" />
</p>

<!-- Contact -->
<p align="center">
  <a href="https://www.linkedin.com/in/dhruv-chaudhary-b64b64371"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:dhruv7chaudhary@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/DhruvPC-ai?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
</p>

<!-- Status -->
<p align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=flat-square&logo=github&logoColor=white" alt="Open to work" />
  <img src="https://img.shields.io/badge/Experience-1%2B%20Year%20Production-0ea5e9?style=flat-square" alt="Experience" />
  <img src="https://img.shields.io/badge/Looking%20for-Software%20Dev%20%2F%20Backend%20Roles-0f766e?style=flat-square" alt="Looking for" />
</p>

---

## 🙋‍♂️ About Me

<p align="center">
  <img src="https://img.shields.io/badge/250%2B-Merged%20MRs-0ea5e9?style=for-the-badge&labelColor=1e1e2e" alt="250+ merged MRs" />
  <img src="https://img.shields.io/badge/30%2B-Security%20Fixes-ef4444?style=for-the-badge&labelColor=1e1e2e" alt="30+ security fixes" />
  <img src="https://img.shields.io/badge/1.4s%20%E2%86%92%201ms-Query%20Speedup-22c55e?style=for-the-badge&labelColor=1e1e2e" alt="1.4 s to 1 ms" />
  <img src="https://img.shields.io/badge/10%2B-Live%20Platforms-f97316?style=for-the-badge&labelColor=1e1e2e" alt="10+ live platforms" />
</p>

I'm a **Software Developer** with **1+ year of hands-on production experience** building, securing and optimising **PHP / PostgreSQL** web platforms, including a domain marketplace, a domain registrar, analytics tools and content sites. I enjoy hunting down slow queries, closing security holes and making production errors disappear.

- 🛠️ **Backend:** PHP 8, PostgreSQL & ClickHouse, from `EXPLAIN ANALYZE` and index design to lock-contention fixes
- 🔐 **Security:** fixed 30+ audit findings (SQL injection, shell injection, IDOR, open redirects) and hardened token & secrets handling
- 🐞 **Reliability:** resolved 45+ production errors triaged through Sentry
- 🤖 **AI / ML:** built an NLP-powered FAQ chatbot with Keras
- 🎓 **Education:** B.E. Computer Engineering, Shivajirao S. Jondhale College of Engineering (2024)
- 🚀 **Now:** open to Software Developer / Backend Engineer roles

---

## ⚡ Production Highlights

```sql
-- Admin report query, before vs after a composite index
EXPLAIN ANALYZE SELECT ...;
--  before:  ~1.4 s   (sequential scan)
--  after:   ~1 ms    (index scan)  🚀
```

| Area | What I did |
|------|------------|
| 🗄️ **Query performance** | Used `EXPLAIN ANALYZE` + `pg_stat_statements` to find slow queries; added composite, partial & covering indexes that turned slow auction queries into index-only scans |
| 🔒 **Locking** | Fixed 55-second statement timeouts in auction cancellation & logout by diagnosing lock contention and adding bounded lock timeouts with retries |
| 🛡️ **Security** | Replaced predictable reset/activation tokens with random SHA-256-hashed tokens; moved hard-coded encryption keys into environment config |
| 📈 **Analytics** | Migrated geo reporting (API + scheduled reports) from PostgreSQL aggregate tables to ClickHouse |
| 🧠 **Memory** | Fixed PHP out-of-memory failures on 10,000-domain searches by removing unneeded per-row lookups |
| 🚨 **Error triage** | Silenced an invalid-input error firing ~2,600 times a week with server-side input validation |
| 🔗 **Features** | Built broken-link monitoring for two content sites, with an admin page featuring sorting, pagination & bulk resolve |

---

## 💻 Tech Stack

🔤 **Languages**<br/>
<img src="https://skillicons.dev/icons?theme=dark&i=php,js,py,cpp,c,java" alt="Languages" />

🎨 **Web**<br/>
<img src="https://skillicons.dev/icons?theme=dark&i=html,css,jquery" alt="Web" />

🗄️ **Databases**<br/>
<img src="https://skillicons.dev/icons?theme=dark&i=postgres,mysql,sqlite" alt="Databases" />

🧰 **Tools**<br/>
<img src="https://skillicons.dev/icons?theme=dark&i=git,gitlab,github,linux,bash" alt="Tools" />

➕ **Also**<br/>
<img src="https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=databricks&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse" />
<img src="https://img.shields.io/badge/Smarty-F0C040?style=flat-square&logoColor=black" alt="Smarty" />
<img src="https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white" alt="Apache" />
<img src="https://img.shields.io/badge/Cron%20Jobs-4B5563?style=flat-square&logo=clockify&logoColor=white" alt="Cron Jobs" />
<img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" alt="Sentry" />
<img src="https://img.shields.io/badge/Shortcut-58B1E4?style=flat-square&logo=shortcut&logoColor=white" alt="Shortcut" />
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras" />
<img src="https://img.shields.io/badge/NLP-7c3aed?style=flat-square" alt="NLP" />

🔐 **Web Security**<br/>
<img src="https://img.shields.io/badge/SQL%20Injection%20Prevention-ef4444?style=flat-square" alt="SQL Injection Prevention" />
<img src="https://img.shields.io/badge/Shell%20Injection%20Prevention-ef4444?style=flat-square" alt="Shell Injection Prevention" />
<img src="https://img.shields.io/badge/IDOR%20Fixes-ef4444?style=flat-square" alt="IDOR Fixes" />
<img src="https://img.shields.io/badge/Input%20Validation-ef4444?style=flat-square" alt="Input Validation" />
<img src="https://img.shields.io/badge/Secure%20Token%20Hashing-ef4444?style=flat-square" alt="Secure Token Hashing" />
<img src="https://img.shields.io/badge/Secrets%20Management-ef4444?style=flat-square" alt="Secrets Management" />

---

<p align="center">
  ⭐ Thanks for visiting! Feel free to connect with me. ⭐
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:0f766e&height=120&section=footer" alt="Footer" />
</p>
