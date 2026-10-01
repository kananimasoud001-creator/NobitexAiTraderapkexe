# Nobitex AI Trader — نسخه مستقل

این نسخه برای اجرای برنامه به VPS، Render، Firebase یا GitHub وابسته نیست.

## خروجی
- Windows EXE
- Android APK (نیازمند Android SDK/Gradle برای Build)

## وضعیت فعلی
- Paper Trading: فعال
- Live Trading: خاموش
- انتقال/برداشت دارایی: وجود ندارد
- توقف اضطراری: فعال
- دریافت داده بازار: مستقیم از API عمومی نوبیتکس
- موتور AI فعلاً baseline ایمن است و خودش را به‌عنوان پیش‌بینی قطعی سود معرفی نمی‌کند.

## Windows
`npm install`
سپس:
`npm run build:electron`
Installer در `dist/` ساخته می‌شود.

## Android
برای APK باید پروژه Android با Capacitor/Android SDK ساخته شود. این بسته هسته مشترک و رابط را آماده کرده است.

## امنیت
API Key واقعی نباید داخل سورس یا فایل قابل انتشار قرار گیرد. قبل از Live Trading باید Secure Storage، محدودیت دسترسی API، مدیریت خطا و تست کامل اضافه شود.
