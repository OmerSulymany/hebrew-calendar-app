# לוח שנה עברי – אפליקציית אנדרואיד

## דרך א׳: בנייה אוטומטית ב-GitHub (בלי להתקין כלום)
1. צרו מאגר (repo) חדש ב-GitHub והעלו אליו את כל תוכן התיקייה הזו.
2. עברו ללשונית **Actions** ← **Build APK** ← **Run workflow**.
3. כשהריצה מסתיימת (כ-4 דקות), הורידו את `hebrew-calendar-apk` מסעיף Artifacts.
4. פתחו את ה-ZIP, והעבירו את `app-debug.apk` לטלפון.
   (בטלפון יש לאשר "התקנה ממקורות לא ידועים".)

## דרך ב׳: בנייה מקומית עם Android Studio
```
npm install
npm run android:sync
npx cap open android
```
ב-Android Studio: Build ← Build APK(s).

## עדכון האפליקציה
ערכו את `src/App.jsx`, ואז הריצו שוב את אחת הדרכים.
