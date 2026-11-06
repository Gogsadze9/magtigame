# Magti Game - Android აპლიკაცია

შენი თამაში - 5 ტური, სუპერ ახტომა, ხმები, ფოთლები, გეიმერი ფინიშზე - ახლა Android აპლიკაციად!

## რა არის შიგნით?
- app/src/main/assets/game/index.html - მთლიანი თამაში (გმირის 4 პოზა + სირბილის 2 კადრი + ფოთლის მონეტა + ფინიშის გეიმერი)
- app/src/main/java/com/magti/game/MainActivity.kt - WebView აპი, fullscreen, ეკრანი არ ითიშება
- AndroidManifest.xml - სახელი: Magti Game, landscape

## როგორ ავაწყო APK - 2 წუთში

### გზა 1 - Android Studio (რეკომენდებული)
1. გახსენი Android Studio -> Open -> აირჩიე ეს საქაღალდე MagtiGame-Android
2. დაელოდე Gradle Sync-ს
3. ტელეფონი შეაერთე USB-ით (Developer Options -> USB Debugging) ან აირჩიე Emulator
4. დააჭირე Run
5. APK-სთვის: Build -> Build App Bundle(s) / APK(s) -> Build APK(s)

### გზა 2 - ტელეფონზე პირდაპირ PWA-თ (APK-ის გარეშე, 10 წამში)
1. ტელეფონის Chrome-ში გახსენი თამაშის ლინკი
2. მენიუ -> Add to Home Screen / Install App
3. ხატულა გაჩნდება აპლიკაციებშივე - სრულ ეკრანზე იშლება, როგორც ნამდვილი აპი

## კონტროლი Android-ზე
- მარცხნივ / მარჯვნივ ღილაკები ეკრანზე
- Jump - ხტომა, SUPER - სუპერ ახტომა (ორჯერ დაჭერა)
- M - ხმის ჩართვა/გამორთვა
- R - ტურის თავიდან დაწყება
