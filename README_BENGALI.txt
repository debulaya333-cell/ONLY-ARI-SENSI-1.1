ONLY ARI SENSI — AndroidIDE/M4Coding compatible project

এই ZIP-এ রয়েছে:
- আগের ONLY ARI SENSI HTML/CSS/JavaScript UI (app/src/main/assets/index.html)
- Android Java code for Display over other apps permission
- draggable ONLY ARI floating shortcut over other apps

এই সংস্করণটি পুরোনো AndroidIDE/M4Coding Gradle 6.1.1-এর জন্য তৈরি:
- Android Gradle Plugin 4.0.2
- compileSdk 30
- Java 8 source compatibility

AndroidIDE-তে:
1. ZIP extract করো।
2. AndroidIDE-তে OnlyAriSensiNative project খুলে নাও।
3. Gradle/JDK setting-এ JDK 8 থাকলে সেটি ব্যবহার করো (Gradle 6.1.1 Java 17-এ চলে না)।
4. Terminal-এ project root থেকে চালাও: gradle assembleDebug
5. সফল হলে APK থাকবে: app/build/outputs/apk/debug/app-debug.apk
6. Install করে প্রথমবার Display over other apps permission Allow করো।

নোট: এই project source code; prebuilt APK নয়। প্রথম build-এ internet লাগবে, কারণ Android Gradle Plugin/SDK dependencies নামবে। ফোনে পর্যাপ্ত storage ও RAM রাখবে।
Floating shortcut শুধু app খুলবে; Free Fire-এর game memory/settings পরিবর্তন করে না এবং auto-aim/cheat করে না।
