# 🤖 Smart Home League — Team Kit · بسته‌ی تیم

سلام تیم! همه‌چیز برای تمرین، کدنویسی و مسابقه همین‌جاست — بدون نصب، بدون اینترنت.

## اجرا · Run it
1. روی **`index.html`** دوبار کلیک کن — همین. (یا `serve.bat` که مرورگر را با
   سرور محلی باز می‌کند؛ هر دو کار می‌کنند، هیچ نصبی لازم نیست.)
2. اگر از serve.bat رفتی: **http://localhost:8801/**

## هر رده سه چیز دارد · Every league gives you three things
| چی | کجا |
|---|---|
| **بیس‌کد · base code** | دکمه‌ی «Base code .py» در منوی حین بازی، یا `leagues/vacuum/<رده>/program.py` — نقطه‌ی شروعِ شرح‌داده‌شده‌ی دوزبانه |
| **راهنما · the guide** | `rulebook.html` (قوانین کامل با عکس) + 📖 Rules داخل بازی + `leagues/vacuum/<رده>/README.md` (سنسورهای همان رده) |
| **ربات‌های آموزشی** | منوی «ربات‌های آماده»: wallfollow، easymoves، goto، hunter… بخوان، بفهم، بهتر کن |

## از کجا شروع کنم؟
1. `rulebook.html` را بخوان.
2. رده‌ات را انتخاب کن؛ از منوی ☰: **Tutorial**، بعد **هلپرها**
   (FS: بلاکی + AI · U14: AI با قطب‌نما · U19: هلپر مسیر)، بعد **ادیتور**.
3. در **Match mode** برنامه‌ات را مقابل ربات‌های آماده تست کن.

## نقشه‌ی مسابقه · Installing a competition map
برگزارکننده یک فایل به اسم **`map1.json`** (یا `map1.html`) می‌دهد.
**فقط همین فایل را کنار `serve.bat` کپی کن** (همان پوشه‌ای که `index.html` هست).
بازی را باز کن؛ خودش پیدا می‌کند، در منوی نقشه با 📁 می‌آید و انتخاب می‌شود.
اگر با برنامه‌ی `.exe` بازی می‌کنی، فایل را کنار خودِ exe بگذار. همین.
*Copy `map1.json` next to `serve.bat` (or next to the .exe). The game finds it by itself.*

## چه چیزی تحویل بدهیم؟ · What you submit
فقط **یک فایل `.py`** برای هر رده — همان که هلپر/ادیتور می‌سازد
(دکمه‌ی Download .py). قبل از تحویل حتماً در Match mode تستش کن.

Good luck — clean fast, steal faster! 🧹
