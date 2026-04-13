# 🎯 Dork dasar (langsung cari file config)

```
site:target.com ext:env
site:target.com ext:ini
site:target.com ext:cfg
site:target.com ext:conf
site:target.com ext:config
site:target.com ext:yaml | ext:yml
```

---

# 🔑 Dork dengan keyword sensitif (lebih tajam)

```
site:target.com ext:env intext:"DB_PASSWORD"
site:target.com ext:env intext:"API_KEY"
site:target.com ext:env intext:"SECRET_KEY"
site:target.com ext:env intext:"ACCESS_TOKEN"
site:target.com ext:env intext:"SMTP"
```

---

# 💀 Cari credential langsung di config lain

```
site:target.com ext:ini intext:"password"
site:target.com ext:cfg intext:"password"
site:target.com ext:conf intext:"password"
site:target.com ext:yaml intext:"password"
site:target.com ext:yml intext:"secret"
```

---

# 🔥 Advanced (sering dapet yang real)

```
site:target.com ext:env"DB_HOST"
site:target.com ext:env"DB_USERNAME"
site:target.com ext:env"MAIL_PASSWORD"
site:target.com ext:env"AWS_SECRET"
site:target.com ext:env"PRIVATE_KEY"
```

---

# ⚡ Kombinasi brutal (high chance valid)

```
site:target.com ext:env"DB_PASSWORD""DB_USERNAME"
site:target.com ext:env"API_KEY""SECRET"
site:target.com ext:yaml"password""username"
```

---

# 🚨 Bonus (file config sering tersembunyi)

```
site:target.com".env"
site:target.com"config.yaml"
site:target.com"settings.yml"
site:target.com"application.conf"
```

---


