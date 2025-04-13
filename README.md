# 🔐 leaky-regexes: Advanced Regex Patterns for Secret Detection

**SecretHound** is a collection of advanced regular expressions crafted to detect hardcoded secrets in codebases, configurations, and logs. Designed for use in bug bounty, red teaming, pentests, and CI/CD pipelines, it helps uncover credentials, tokens, private keys, and other sensitive data.

---

## 📁 Features

- 🎯 API keys & tokens (Google, Facebook, Twitter, etc.)
- 🔐 OAuth2, JWT, AWS/GCP/Azure access keys
- 🗝️ Private keys (.pem, .key, .p12, etc.)
- 🔎 Hardcoded usernames and passwords
- 🌐 Webhook URLs (Slack, Discord, etc.)
- 💾 Database connection strings (MongoDB, PostgreSQL, MySQL, etc.)
- ☁️ Cloud provider secrets
- 📲 Mobile app embedded secrets
- 🧩 Custom patterns for specific technologies and frameworks

---

## ⚙️ Usage Examples

### 🔎Grep (Quick Local Search)

```bash
grep -EiR --color=always -f regex.txt
```
