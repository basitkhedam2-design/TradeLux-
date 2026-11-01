TradeLux Android Project (Android 14 compatible project setup)

دا د Android Studio پروژه ده، APK لا نه دی.

د APK جوړولو لپاره:
1) دا ZIP په کمپیوټر کې Extract کړئ.
2) Android Studio خلاص کړئ او Open ووهئ.
3) د TradeLux_Android_Project فولډر انتخاب کړئ.
4) د Gradle Sync بشپړېدو ته انتظار وباسئ.
5) Build > Build Bundle(s) / APK(s) > Build APK(s) وټاکئ.
6) APK د app/build/outputs/apk/debug/app-debug.apk په ځای کې پیدا کېږي.

مهم:
- پروژه د Android 14 ټابلیټ لپاره برابره شوې (minSdk 23، targetSdk 35).
- اپلیکیشن انټرنېټ permission نه غواړي او HTML د اپ دننه ساتل شوی.
- معلومات د WebView local storage کې ساتل کېږي؛ د اپ پاکول/Uninstall کول یې له منځه وړلی شي.
- دا لومړنی Android wrapper دی، نه د Google Play لپاره release-signed APK.
- د اصلي کاروبار لپاره تر استعمال مخکې ټولې معاملې او backup/restore په ازمایښتي معلوماتو وازمویئ.
