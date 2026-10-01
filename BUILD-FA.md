# ساخت خودکار APK و EXE

این نسخه از برنامه برای اجرای نهایی به VPS، Render یا Firebase وابسته نیست.

## Android
Workflow با GitHub Actions یک پروژه Android موقت می‌سازد، Capacitor را اضافه و Sync می‌کند و سپس APK آزمایشی Debug را می‌سازد.

## Windows
Workflow روی Windows Runner، Electron را نصب و با electron-builder فایل Installer را تولید می‌کند.

## فعال‌سازی
در GitHub به Actions بروید و:
- Build Android APK → Run workflow
- Build Windows EXE → Run workflow

بعد از پایان، از بخش Artifacts فایل APK یا EXE را دریافت کنید.

## نکته
این خروجی‌ها نسخه آزمایشی هستند. برای انتشار عمومی Android باید APK با کلید امضای اختصاصی Release امضا شود. Windows نیز برای حذف هشدارهای اعتماد، به Code Signing نیاز دارد.

Live Trading همچنان خاموش است و انتقال/برداشت دارایی در برنامه وجود ندارد.
