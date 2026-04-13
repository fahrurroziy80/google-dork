# 

---

# 🎯 1. File konfigurasi & credential (HIGH VALUE)

```
site:target.com ext:env
site:target.com ext:ini
site:target.com ext:cfg
site:target.com ext:conf
site:target.com ext:config
site:target.com ext:yaml | ext:yml
```

👉 sering berisi:

- API key
- DB password
- secret token

---

# 💀 2. Backup & database dump (JACKPOT)

```
site:target.com ext:sql
site:target.com ext:db
site:target.com ext:sqlite
site:target.com ext:bak
site:target.com ext:old
site:target.com ext:backup
site:target.com ext:zip | ext:rar | ext:7z
```

👉 ini bisa langsung:

- full database leak 🚨

---

# 🔑 3. Log & debug file

```
site:target.com ext:log
site:target.com ext:txt"error"
site:target.com"stack trace"
site:target.com"exception"
```

👉 sering bocor:

- path server
- token
- query SQL

---

# 📊 4. Data pribadi (PII)

```
site:target.com ext:xlsx
site:target.com ext:csv
site:target.com ext:pdf
```

Lebih spesifik:

```
site:target.com ext:xlsx intext:nik
site:target.com ext:csv intext:email
site:target.com ext:pdf intext:"nama lengkap"
site:target.com ext:xlsx"no hp"
```

---

# 🔐 5. Credential exposure

```
site:target.com intext:"username" intext:"password"
site:target.com intext:"login" intext:"admin"
site:target.com"api_key"
site:target.com"secret="
site:target.com"access_token"
```

---

# 📁 6. Directory listing (MUDAH BANGET dapet data)

```
site:target.com intitle:"index of"
site:target.com intitle:"index of""parent directory"
```

---

# 🧠 7. File upload / storage

```
site:target.com inurl:uploads
site:target.com inurl:files
site:target.com inurl:storage
```

---

# 🔥 8. Advanced combo (lebih tajam)

---
```
site:target.com ext:xlsx"nama""alamat"
site:target.com ext:csv"email""password"
site:target.com ext:log"api"
site:target.com ext:env"DB_PASSWORD"
```
---
