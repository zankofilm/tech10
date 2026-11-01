# اصلاح Build در GitHub Actions

در 2026-11-01 اجرای GitHub Actions با خطای `Failed to find package 'tools'` در اکشن قدیمی `android-actions/setup-android@v3` متوقف می‌شد.

اصلاح انجام‌شده:

- ارتقا به `android-actions/setup-android@v4`
- تعیین صریح `packages: "platform-tools"`
- حفظ Android Platform 35 و Build Tools 35.0.0
- حفظ Gradle 8.9 و JDK 17

هیچ‌یک از منطق ورود، Biometric، WebView، همگام‌سازی ۵ ثانیه‌ای، آپلود/دانلود، دوربین یا چاپ در این اصلاح حذف یا تغییر داده نشده است.
