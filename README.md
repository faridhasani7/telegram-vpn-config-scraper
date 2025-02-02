# telegram-vpn-config-scraper
A web scraper that extracts VPN configuration links (vmess, vless, Shadowsocks, Trojan) from multiple Telegram channels.

# Telegram VPN Config Scraper

## Overview
This project is a web scraper designed to extract VPN configuration links (vmess, vless, Shadowsocks, Trojan) from multiple Telegram channels. It parses the channels' HTML content using BeautifulSoup and categorizes the configurations into separate files.

## Features
- Extracts VPN configuration links from a list of Telegram channels.
- Supports multiple protocols: vmess, vless, Shadowsocks, and Trojan.
- Saves each protocol's configurations into its own text file.
- Uses `requests` for HTTP requests and `BeautifulSoup` for HTML parsing.

## Installation
Clone the repository and install the required packages:
```bash
git clone https://github.com/faridhasani7/telegram-vpn-config-scraper.git
cd telegram-vpn-config-scraper
```

Run the script using:

```bash
python main.py
```

#The extracted configuration links will be saved into text files named according to their protocol (e.g., vmess_iran.txt, vless_iran.txt, etc.).

## Requirements
```bash
requests
beautifulsoup4
```

## License
This project is licensed under the MIT License.

# اسکریپر کانفیگ VPN تلگرام

## معرفی
این پروژه یک اسکریپر وب است که لینک‌های کانفیگ VPN (شامل vmess، vless، Shadowsocks و Trojan) را از چندین کانال تلگرام استخراج می‌کند. این اسکریپر با استفاده از BeautifulSoup محتوای HTML کانال‌ها را پردازش کرده و کانفیگ‌ها را به فایل‌های متنی جداگانه بر اساس پروتکل دسته‌بندی می‌کند.


## ویژگی‌ها
- استخراج لینک‌های کانفیگ VPN از لیست کانال‌های تلگرام.
- پشتیبانی از چندین پروتکل: vmess، vless، Shadowsocks و Trojan.
- ذخیره‌ی کانفیگ‌های هر پروتکل در فایل متنی مخصوص به آن (مثلاً: `vmess_iran.txt`، `vless_iran.txt` و ...).
- استفاده از `requests` برای ارسال درخواست‌های HTTP و `BeautifulSoup` برای پردازش HTML.



## اجرا
برای اجرای اسکریپت، دستور زیر را اجرا کنید:
```bash
python main.py
```
لینک‌های استخراج شده در فایل‌های متنی به نام‌های مربوط به هر پروتکل (مانند vmess_iran.txt، vless_iran.txt و ...) ذخیره خواهند شد.

نیازمندی‌ها
```bash
requests
beautifulsoup4
```
لایسنس
این پروژه تحت مجوز MIT منتشر شده است.
