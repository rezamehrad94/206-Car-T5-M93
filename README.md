# دفترچه سرویس ماشین (PWA)

اپ فارسی برای ثبت سرویس‌های دوره‌ای، تعویض قطعات، بنزین و مدارک ماشین. بدون سرور؛ داده‌ها روی خود دستگاه ذخیره می‌شود و بدون اینترنت هم کار می‌کند.

## انتشار روی GitHub Pages
```bash
cd car-logbook
git init
git add .
git commit -m "Car logbook PWA"
git branch -M main
git remote add origin https://github.com/USERNAME/car-logbook.git
git push -u origin main
```
بعد در GitHub: Settings ← Pages ← Source: `Deploy from a branch` ← Branch: `main` / `(root)` ← Save.
آدرس: `https://USERNAME.github.io/car-logbook/`

## افزودن به هوم‌اسکرین (iPhone)
1. آدرس بالا را در **Safari** باز کنید.
2. Share ← Add to Home Screen.

## آپدیت
تغییر را commit و push کنید؛ با اینترنت، نسخه‌ی جدید خودکار می‌آید. اگر تغییر نکرد، در `sw.js` عدد `V` را بالا ببرید (`car206-v2`).

## نکته
داده‌ها در حافظه‌ی همان مرورگر/اپ هستند. گاهی از «بیشتر ← کپی پشتیبان» استفاده کنید.
