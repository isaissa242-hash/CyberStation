CyberStation - Android Offline APK

هذا المشروع يحول ملف cyberstation_2030_updated-3.html إلى تطبيق Android مستقل.
الصفحة تُحمّل من داخل APK عبر WebView محلي:
file:///android_asset/index.html

لا يعتمد التطبيق على Vercel أو Chrome أو الإنترنت.

البناء:
1) افتح المجلد في Android Studio.
2) انتظر Gradle Sync.
3) من القائمة: Build > Build APK(s).
4) ملف APK سيكون داخل app/build/outputs/apk/debug/.

ملاحظة: هذه البيئة لا تحتوي Android SDK/Gradle، لذلك لم أستطع إخراج APK ثنائي جاهز هنا.


طريقة الهاتف فقط: ارفع مجلد المشروع إلى GitHub ثم افتح Actions واختر Build CyberStation APK وشغّل Run workflow. بعد نجاح البناء نزّل artifact باسم CyberStation-Offline-APK ثم فك ضغطه وثبّت app-debug.apk.
