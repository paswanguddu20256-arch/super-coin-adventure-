# Super Coin Adventure 🪙 (2D Platformer Game & Android APK)

"Super Coin Adventure" ek mazedaar aur thrilling 2D Platformer Game hai jisme player daudta hai, koodta hai, sone ke sikke batorta hai, dushmano ke upar koodkar (stomp) unhe harata hai aur 3 alag-alag levels paar karta hai!

Ye project React + TypeScript + HTML5 Canvas aur Capacitor se tayar kiya gaya hai, jise asani se Android APK mein compile karke kisi bhi Android phone mein install kiya ja sakta hai.

---

## 📱 Mobile Phone se GitHub par APK kaise banayein aur Download karein? (Step-by-Step Guide)

Agar aapke paas computer nahi hai aur aap apne mobile phone se hi APK file banana chahte hain, toh neeche diye gaye aasan steps follow karein:

### Step 1: GitHub Repository par Files Upload / Push karein
1. Apne mobile browser mein **github.com** kholein aur apne account mein login karein.
2. Apni repository kholein jahan ye project maujood hai.
3. Check karein ki saari files (khaaskar `.github/workflows/android-apk.yml`, `android/`, `src/`, aur `package.json`) maujood hain.

### Step 2: GitHub Actions Tab kholein aur APK Build Run karein
1. Repository ke upar diye gaye tabs mein se **"Actions"** tab par tap karein.
2. Left side mein workflows ki list mein **"Build Super Coin Adventure APK"** par click karein.
3. Wahan ek **"Run workflow"** ka button dikhega.
4. "Run workflow" par click karein aur hari/neeli button **"Run workflow"** daba dein!
5. GitHub ke cloud servers par automatically:
   - Web files build hongi (`npm run build`).
   - Android Capacitor project synchronize hoga (`npx cap sync android`).
   - Gradle se Debug APK compile hoga (`./gradlew assembleDebug`).
6. Is process mein lagbhag 2 se 4 minute lagte hain.

### Step 3: APK Artifact Download karein
1. Jab build ke aage green checkmark (**✔**) aa jaye, toh us workflow run par tap karein.
2. Page ke bilkul neeche scroll karein, wahan **"Artifacts"** section dikhega.
3. Wahan **`SuperCoinAdventure-Debug-APK`** par tap karein.
4. Ek ZIP file download hogi. Apne phone ke File Manager mein jakar us ZIP ko extract karein.
5. Andar aapko **`app-debug.apk`** mil jayegi!

---

## 📲 Phone mein APK Install karne ka Tareeka

1. Apne Android phone mein **Files** ya **Downloads** folder kholein.
2. **`app-debug.apk`** par tap karein.
3. Android ek security warning dikhayega:
   > *"For your security, your phone is not allowed to install unknown apps from this source"* ya *"Blocked by Play Protect"*.
4. **"Settings"** par tap karein aur **"Allow from this source"** (Is source se install allow karein) ko ON karein.
5. Agar Google Play Protect warning aaye, toh **"More details"** par tap karein aur **"Install anyway"** (Fir bhi install karein) chunein.
6. Installation poori hone par aapke phone ki screen par **"Super Coin Adventure"** ka golden coin icon aa jayega.
7. Icon par tap karein aur game ka anand lein!

---

## 🚀 Google Play Store par Publish karne ki Jankari

APK ko apne phone mein chalana aur Google Play Store par publish karna do alag process hain:

1. **Google Play Console Developer Account:**
   - Play Store par game daalne ke liye Google Play Console account ki zaroorat hoti hai ($25 one-time registration fee).
2. **Android App Bundle (.AAB):**
   - Google Play Store ab APK ki jagah **.AAB (Android App Bundle)** maangta hai.
   - GitHub Actions workflow release AAB bhi generate kar deta hai.
3. **App Signing Keystore:**
   - Play Store par upload karne ke liye app ko ek digital keystore se sign karna hota hai.
   - Suraksha ke kaaran secret keystores aur passwords ko public source code mein nahi rakha jata.
4. **PWABuilder Option (Sabse Aasan):**
   - Aap [pwabuilder.com](https://www.pwabuilder.com/) par game ka live link daalkar bhi signed Google Play package 5 minute mein generate kar sakte hain!

---

## 🎮 Game Controls & Features

- **◀ Left Button / A Key:** Baayein daudein
- **▶ Right Button / D Key:** Daayein daudein
- **▲ Jump Button / Space Bar / W:** Koodna (Jump)
- **⏸ Pause Button / P Key:** Game pause karna
- **🪙 Coins:** Har coin se +1 Score
- **👾 Enemies:** Dushman ke sir par koodne se Stomp hoga aur +5 Points milenge!
- **❤️ 3 Lives:** Har level mein 3 dilon ki zindagi milti hai.
- **🚩 3 Levels:** Forest (Level 1), Mountain Clouds (Level 2), Magma Castle (Level 3)!

Enjoy Super Coin Adventure! 🪙✨
