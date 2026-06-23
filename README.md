
# موتوفیکس | MotoFix 🔧

<div dir="rtl">

### ابزار تشخیص هوشمند مشکلات موتورسیکلت برای بازار ایران
**Intelligent Motorcycle Diagnostic Tool for the Iranian Market**

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Status: Active](https://img.shields.io/badge/Status-Active-green.svg)
![Language: Persian](https://img.shields.io/badge/Language-Persian%20(RTL)-orange.svg)
![Platform: Web](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-lightgrey.svg)

---

## 📖 درباره | About

**موتوفیکس** یک ابزار تشخیص قانون‌محور و **بدون نیاز به اینترنت** برای موتورسیکلت‌های بازار خاور ایران است. این ابزار مالکان و تکنسین‌ها را از طریق یک فلو ساختار‌شده از انتخاب علائم، تا فهرست اولویت‌دار علل محتمل، سطح فوریت، راهنمای رانندگی و نکات پیشگیری راهنمایی می‌کند — تمام به فارسی.

**MotoFix** is a rule-based, offline-capable diagnostic wizard for motorcycles sold in Iran's eastern market. It guides owners and technicians through a structured symptom-selection flow and returns a prioritized list of probable causes, urgency level, ride guidance, and prevention tips — all in Persian.

> ساخته شده توسط [بازرگانی اسماعیلی](https://esmaeilitrading.com)  
> Built and maintained by [Esmaeili Trading](https://esmaeilitrading.com)

---

## ✨ ویژگی‌ها | Features

- ✅ **بدون اینترنت** | **Offline-first** — کاملا در مرورگر اجرا می‌شود
- ✅ **یک فایل HTML** | **Single HTML file** — بدون وابستگی، بدون build step
- ✅ **فارسی RTL کامل** | **Persian RTL UI** — کاملا برای کاربران ایرانی محلی‌سازی شده
- ✅ **منطق EFI تخصصی** | **EFI-only logic** — موتورسیکلت‌های سوخت‌رسان شامل (~99% بازار ایران)
- ✅ **14 دسته علامت** | **14 symptom categories** — از شروع سرد تا نویز تعلیق
- ✅ **شناخت نوع گیربکس** | **Transmission-aware** — مسیرهای استدلال جداگانه برای اتوماتیک و دستی
- ✅ **مقیاس فوریت** | **Urgency gauge** — چهار سطح: کم / متوسط / زیاد / بحرانی
- ✅ **گزارش‌های قابل چاپ** | **Printable reports** — صادرات به PDF با یک کلیک
- ✅ **کارت خدمات پس از فروش** | **After-sales card** — لینک مستقیم به مرکز خدمات اسماعیلی

---

## 🚀 شروع سریع | Quick Start

نیازی به نصب نیست. فقط فایل را در هر مرورگر مدرن باز کنید:

No installation needed. Just open the file in any modern browser:

```bash
git clone https://github.com/alireza-esmaeili/moto-fix.git
cd moto-fix
open motofix.html        # macOS
start motofix.html       # Windows
xdg-open motofix.html   # Linux
```

یا [آخرین نسخه را دانلود کنید](https://github.com/alireza-esmaeili/moto-fix/releases) به صورت ZIP.

Or [download the latest release](https://github.com/alireza-esmaeili/moto-fix/releases) as a ZIP.

---

## 🔧 نحوهٔ کار | How It Works

```
1. نوع موتورسیکلت انتخاب کن  →  اتوماتیک یا دستی
   Select motorcycle type  →  Automatic or Geared

2. علامت را انتخاب کن       →  14 دسته، 50+ علامت
   Select symptom          →  14 categories, 50+ symptoms

3. سوالات پیگیری پاسخ بده  →  2–3 سوال روشن‌کننده
   Answer follow-up        →  2–3 clarifying questions

4. گزارش دریافت کن           →  علل · فوریت · راهنمای رانندگی · پیشگیری
   Receive report          →  causes · urgency · ride advice · prevention

5. چاپ یا اشتراک‌گذاری      →  صادرات PDF با یک کلیک
   Print or share          →  one-click PDF export
```

موتور یک درخت قوانین معین است — بدون استنتاج AI در زمان اجرا، بدون فراخوانی شبکه، بدون پیگیری.

The engine is a deterministic rule tree — no AI inference at runtime, no network calls, no tracking.

---

## 📋 دسته‌های تشخیصی | Diagnostic Categories

| # | دسته | Category | نمونه‌ها | Examples |
|---|------|----------|----------|----------|
| 1 | شروع سرد | Cold Start | نمی‌خواند صدا کند، شروع سخت | Won't start, hard to start |
| 2 | دور بیکار | Idle | دور خراب، خاموشی | Rough idle, stalling |
| 3 | قدرت و شتاب | Power & Acceleration | تأخیر، نقاط تخت | Hesitation, flat spots |
| 4 | مصرف سوخت | Fuel Consumption | مصرف بالا، غنی/لاغر | High consumption, rich/lean |
| 5 | سیستم EFI | EFI & Engine Management | چراغ بررسی موتور، خرابی حسگر | Check engine light, sensor faults |
| 6 | الکتریکی | Electrical | باتری، چراغ، بوق | Battery, lights, horn |
| 7 | ترمز | Brakes | اهرم نرم، نویز، محو | Spongy lever, noise, fade |
| 8 | تعلیق | Suspension | تکان‌خوردگی، تاب، سخت | Wobble, bottoming, harsh ride |
| 9 | نویز و لرزش | Noise & Vibration | ضربه، قطقطه، نویز زنجیر | Knocking, rattling, chain noise |
| 10 | روغن و خنک‌کننده | Oil & Coolant | نشتی، گرم‌شدن بیش‌ازحد، روغن شیری | Leaks, overheating, milky oil |
| 11 | ظاهر | Appearance | خوردگی، رنگ، پلاستیک | Corrosion, paint, plastic |
| 12 | ایمنی | Safety | ABS، گاز، آینه | ABS, throttle, mirrors |
| 13 | فصلی | Seasonal | شروع زمستانی، گرمای تابستان | Winter starting, summer heat |
| 14 | نگهداری روتین | Routine Maintenance | یادآوری سرویس، بررسی سیال | Service reminders, fluid checks |

---

## 🎨 سیستم طراحی | Design System

موتوفیکس از یک سیستم طراحی custom مبتنی بر token‌ها استفاده می‌کند که از برند اسماعیلی الهام گرفته شده است.

MotoFix uses a custom token-based design system derived from the Esmaeili brand.

```css
--brand:      #3050E8   /* آبی اصلی | Primary blue */
--brand-2:    #5571FF   /* آبی ثانویه | Secondary blue */
--brand-deep: #1B2C9E   /* آبی عمیق | Deep blue */
--brand-ink:  #16215C   /* جوهر | Ink */
--ok:         #129E68   /* سبز — امن | Green — safe */
--warn:       #D89A1A   /* عنبری — احتیاط | Amber — caution */
--high:       #E5701C   /* نارنجی — فوریت زیاد | Orange — high urgency */
--crit:       #D93A3A   /* قرمز — بحرانی | Red — critical */
```

تایپوگرافی: **Vazirmatn** (رابط کاربری) · **JetBrains Mono** (داده/کدها)  
Typography: **Vazirmatn** (UI) · **JetBrains Mono** (data/codes)

---

## 📊 آمار پروژه | Project Stats

| معیار | Metric | مقدار | Value |
|--------|--------|---------|---------|
| اندازهٔ فایل | File size | ~230 KB | ~230 KB |
| خطوط کد | Lines of code | 1,650+ | 1,650+ |
| توکن‌های طراحی | Design tokens | 40+ | 40+ |
| قوانین تشخیصی | Diagnostic rules | 200+ | 200+ |
| ترکیب علائم | Symptom combinations | 500+ | 500+ |
| نوع موتورسیکلت | Supported bike types | اتوماتیک · دستی | Automatic · Geared |

---

## 🗺️ نقشهٔ راه | Roadmap

- [x] موتور تشخیصی اصلی | Core diagnostic engine
- [x] رابط کاربری فارسی RTL | Persian RTL UI
- [x] گزارش‌های PDF قابل چاپ | Printable PDF reports
- [x] کارت خدمات پس از فروش | After-sales service card
- [ ] تغییر زبان انگلیسی | English language toggle
- [ ] حالت کاربراتوری (موتورهای قدیمی) | Carburetor mode (legacy bikes)
- [ ] اشتراک‌گذاری گزارش QR-code | QR-code report sharing
- [ ] مانیفست Progressive Web App (PWA) | Progressive Web App (PWA) manifest
- [ ] ادغام نقشهٔ تعمیرگاه‌ها | Service locator map integration

---

## 🤝 مشارکت | Contributing

مسائل و درخواست‌های pull خوش‌آمد هستند. اگر موتورسیکلت‌ها را در بازاری با محدودیت‌های مشابه نگهداری می‌کنید (ناوگان EFI غالب، اسکریپت غیر لاتین، محیط‌های بدون اینترنت)، این پایگاه کد ممکن است یک نقطهٔ شروع مفیدی باشد.

Issues and pull requests are welcome. If you maintain motorcycles in a market with similar constraints (EFI-dominant fleet, non-Latin script, offline environments), this codebase may be a useful starting point.

```bash
1. Fork the repo
2. ساخت شاخهٔ ویژگی: git checkout -b feature/english-ui
   Create a feature branch: git checkout -b feature/english-ui
3. Commit تغییرات: git commit -m "اضافه کردن تغییر زبان انگلیسی"
   Commit your changes: git commit -m "Add English UI toggle"
4. فشار دهید و درخواست Pull بازکنید
   Push and open a Pull Request
```

---

## ⚠️ سلامت و ایمنی | Disclaimer

موتوفیکس یک **کمک تشخیصی نخستین** است، جایگزین یک مکانیک واجد‌شرایط نیست. برای نتایج **بحرانی** یا **فوریت زیاد**، رانندگی را متوقف کنید و قبل از استفادهٔ بیشتر با یک تکنسین معتبر مشورت کنید.

MotoFix is a **first-line diagnostic aid**, not a replacement for a qualified mechanic. For Critical or High urgency results, stop riding and consult a certified technician before further use.

---

## 📄 مجوز | License

[MIT](LICENSE) © 2024 Alireza Esmaeili, Esmaeili Trading

---

## 👨‍💻 نویسنده | Author

**علیرضا اسماعیلی** | **Alireza Esmaeili**  
بنیان‌گذار، [بازرگانی اسماعیلی](https://esmaeilitrading.com)  
Founder, [Esmaeili Trading](https://esmaeilitrading.com)

نمایندهٔ رسمی Yamaha · Benelli · Honda 
Official Yamaha · Benelli · Giant dealership — Eastern Iran

📧 alirezaesmaili9@gmail.com 
🌐 esmaeilitrading.com

</div>

---

<div>

**[بازگشت به بالا](#موتوفیکس--motofix-) | [Back to top](#موتوفیکس--motofix-)**

</div>
