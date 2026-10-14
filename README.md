# Olma Market — Muddat nazorati

## O'rnatish (bir marta, ~10 daqiqa, tekis bepul tarif)
1. https://console.firebase.google.com → **Add project**.
2. **Build → Authentication → Sign-in method → Email/Password** ni yoqing.
3. **Build → Firestore Database → Create database**.
4. **Project settings → Your apps → Web (</>)** → chiqqan `firebaseConfig` ni `index.html` ichiga qo'ying.
5. Kompyuterda: `npm i -g firebase-tools`, shu papkada `firebase login`, `firebase init`
   (mavjud loyihani tanlang, fayllarni ustiga yozmang), so'ng
   `firebase deploy --only firestore:rules,hosting`
6. Havola: `https://LOYIHA.web.app` — shuni xodimlarga yuboring. Telefonda "Ekranga qo'shish" qiling.
