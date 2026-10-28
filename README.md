# 🌍 سابسکریپشن Shadowmere بر اساس کشور

[![Subscription Update](https://github.com/amepartito/usa-sub/actions/workflows/update.yml/badge.svg)](https://github.com/amepartito/usa-sub/actions/workflows/update.yml)

**26 کشور و 218 کانفیگ** در آخرین خروجی ثبت شده‌اند. فقط سرورهای دارای پرچم معتبر در سابسکریپشن فعال Shadowmere دسته‌بندی می‌شوند.

## 🔗 استفاده سریع

آدرس پایه:

```text
https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/
```

فقط **دو حرف کد کشور را به انتهای آدرس اضافه کن**؛ همه کدها کوچک هستند. مثال:

| کشور | کد | سابسکریپشن |
|---|---|---|
| 🇺🇸 آمریکا | `us` | [باز کردن لینک](https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/us) |
| 🇫🇷 فرانسه | `fr` | [باز کردن لینک](https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/fr) |
| 🇩🇪 آلمان | `de` | [باز کردن لینک](https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/de) |
| 🇬🇧 بریتانیا | `gb` | [باز کردن لینک](https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/gb) |
| 🇳🇱 هلند | `nl` | [باز کردن لینک](https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/nl) |
| 🇨🇦 کانادا | `ca` | [باز کردن لینک](https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/ca) |
| 🇯🇵 ژاپن | `jp` | [باز کردن لینک](https://raw.githubusercontent.com/amepartito/usa-sub/main/subs/jp) |

**[📋 فهرست کامل کشورها، تعداد سرورها و لینک هر کشور](https://github.com/amepartito/usa-sub/blob/main/COUNTRIES.md)**

اگر کشوری در فهرست نیست، یعنی در آخرین دریافت موفق، سرور فعالِ برچسب‌دار برای آن پیدا نشده است.

## 📱 نصب در Hiddify یا Streisand

1. لینک کشور موردنظر را از جدول بالا یا فایل `COUNTRIES.md` کپی کن.
2. در برنامه، گزینه افزودن پروفایل یا سابسکریپشن با URL را انتخاب کن.
3. لینک را وارد کن و پروفایل را به‌روزرسانی کن.
4. در دفعات بعد، همان لینک ثابت را نگه دار و پروفایل را Refresh/Update کن.

## 🔄 به‌روزرسانی خودکار

- GitHub Actions هر **۳ ساعت** برای دریافت اطلاعات جدید تلاش می‌کند؛ زمان‌بندی ممکن است با تأخیر اجرا شود.
- در [صفحه Actions](https://github.com/amepartito/usa-sub/actions/workflows/update.yml) می‌توان نتیجه اجراها را دید و `Run workflow` را دستی اجرا کرد.
- اگر دریافت داده خراب شود، Workflow با خطا متوقف می‌شود و فایل‌های منتشرشده قبلی تغییر نمی‌کنند.
- فایل‌های کشورهایی که دیگر در خروجی معتبر نباشند از فهرست حذف می‌شوند.

## 🧹 ساختار فایل‌ها

```text
subs/us      آمریکا
subs/fr      فرانسه
subs/de      آلمان
...          سایر کشورهای موجود
COUNTRIES.md  فهرست خودکار کشورها و لینک‌ها
README.md     همین راهنمای فارسی
```

دیگر فایلی به نام `us.txt` در ریشه مخزن یا فایل‌های تکراری `subs/us.txt` و مشابه آن منتشر نمی‌شود. **آدرس قدیمی `.../main/us.txt` را از برنامه پاک کن و از `.../main/subs/us` استفاده کن.**

## ⚠️ نکات مهم

- منبع: [Shadowmere](https://shadowmere.xyz/)؛ پروتکل خروجی: **Shadowsocks** و فرمت سابسکریپشن: **Base64**.
- فعال بودن نزد Shadowmere تضمین نمی‌کند سرور از شبکه یا کشور تو متصل شود.
- کد کشور از **پرچمِ نام کانفیگ** خوانده می‌شود، نه با آزمایش موقعیت IP.
- این پروژه فقط کانفیگ‌های موجود در منبع را دسته‌بندی می‌کند؛ خودش سرور VPN ارائه نمی‌کند.
- کدها معمولاً با ISO 3166-1 alpha-2 منطبق‌اند؛ برای بریتانیا `gb` است.
