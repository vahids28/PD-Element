

# 🇮🇷 نسخه فارسی

## 🧩 معرفی

**Matrix Stack Manager** یک اسکریپت حرفه‌ای برای نصب و مدیریت کامل سرور:

- Matrix Synapse
- Element Web
- TURN Server (coturn)
- Nginx + SSL (Let's Encrypt)

این اسکریپت به شما اجازه می‌دهد با چند کلیک یک سرور چت مشابه تلگرام / واتساپ راه‌اندازی کنید — کاملاً روی سرور خودتان.

---

## ✨ امکانات اصلی

### 🔧 نصب کامل خودکار
- نصب Synapse
- نصب PostgreSQL یا SQLite
- نصب Nginx
- دریافت خودکار SSL
- نصب Element Web
- تنظیم .well-known
- تنظیم TURN برای تماس صوتی و تصویری

---

### 👥 مدیریت کاربران
- ساخت ادمین
- ساخت کاربر معمولی
- ساخت کاربر با پسورد رندوم
- ری‌اکتیو کردن کاربر
- لیست کاربران
- غیرفعال‌سازی کاربر

---

### 📦 مدیریت آپلود
- تغییر همزمان:
  - Nginx `client_max_body_size`
  - Synapse `max_upload_size`

---

### 🧾 کنترل ثبت‌نام
- فعال / غیرفعال کردن ثبت‌نام عمومی
- جلوگیری از اسپم بعد از ساخت کاربران

---

### 🔎 Health Check
- بررسی وضعیت سرویس‌ها
- بررسی API ماتریکس
- بررسی .well-known
- بررسی پورت‌ها
- بررسی SSL

---

### 🧰 Fix Wizard
رفع خودکار مشکلات رایج:
- لینک نبودن vhost
- فعال نبودن coturn
- خطای nginx
- ری‌استارت سرویس‌ها

---

### 💾 Backup / Restore
- بکاپ کامل از:
  - دیتابیس
  - تنظیمات
  - nginx
  - turn
  - SSL (اختیاری)
- ریستور کامل

---

### ⬆️ آپدیت Element
- آپدیت به نسخه خاص
- دریافت آخرین نسخه از GitHub API
- حفظ config.json

---

### 🧨 حذف کامل (Purge)
حذف کامل تمام اجزای استک

---

## 🗄️ پایگاه داده

پشتیبانی از:

- SQLite (ساده)
- PostgreSQL (پیشنهادی برای Production)

> برای سرورهای واقعی و چندکاربره، PostgreSQL توصیه می‌شود.

---

## 📱 سازگار با

- Element Web
- Element Mobile
- Element X
- سایر کلاینت‌های Matrix

---

## ⚙️ سیستم مورد نیاز

- Ubuntu 20.04 / 22.04
- دسترسی Root
- دامنه متصل به IP سرور
- پورت‌های 80 و 443 باز

---

## 🚀 نصب سریع

```bash
bash <(curl -Ls https://raw.githubusercontent.com/vahids28/PD-Element/main/install.sh)
```

---

## 📌 نسخه فعلی

**Version: 1.5**

---

## 🔗 لینک‌ها

Telegram: https://t.me/MYoutub  
YouTube: https://www.youtube.com/@ParsDigital  

---

## 🛣️ Roadmap

- Sliding Sync installer (PRO)
- PostgreSQL auto-migration
- Multi-worker Synapse mode
- Advanced monitoring

---
