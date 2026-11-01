TradeLux Android APK Project

دا د Android اصلي پروژه ده چې د TradeLux آفلاين پاڼه د Android WebView دننه پرانيزي.
دا ZIP خپله APK نه ده؛ GitHub Actions به APK جوړ کړي.

د جوړولو لنډه لاره:
1. د GitHub خپل TradeLux- repository ته لاړ شئ.
2. د پخوانیو پروژوي فایلونو پر ځای د دې ZIP ټول فایلونه upload/replace کړئ.
   مهم: د ZIP دننه .github فولډر هم upload کړئ.
3. ټول بدلونونه commit کړئ.
4. د Actions برخه کې "Build TradeLux APK" run وګورئ.
5. که شین (Success) شو، د run پاڼې لاندې Artifacts کې TradeLux-APK ښکته کړئ.
6. ZIP extract کړئ او app-debug.apk په Samsung ټابلیټ کې نصب کړئ.

د APK ځانګړنې:
- Android applicationId: com.tradelux.app
- Minimum Android: 6.0 (API 23)
- Target Android: 15 (API 35)
- Offline HTML asset په APK کې دننه دی؛ لومړی ځل انټرنېټ ته اړتیا نه لري.

مهم او رښتینی وضاحت:
- دا پروژه APK جوړولو ته چمتو شوې، خو APK تر هغه نه ده تایید شوې چې GitHub Actions په بریالیتوب build نه وي کړې.
- په دننه کې د TradeLux HTML نسخه ده. ځینې پرمختللې حسابدارۍ کړنې لا بشپړې/حسابرسي شوې نه دي. د حقیقي حسابونو لپاره تر بشپړې ازموینې مخکې یوازینۍ سرچینه مه ګرځوئ.
- د اپ دننه معلومات د همدې وسیلې په WebView ذخیره کې ساتل کېږي. Backup په منظم ډول واخلئ.
