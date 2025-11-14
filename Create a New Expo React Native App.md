✅ 1. Create a New Expo React Native App
Terminal / CMD / PowerShell me run karein:

    npx create-expo-app my-ecommerce-app

    NOTE:
    | my-ecommerce-app ko aap apne brand ke naam se replace kar sakte ho
    | jaise: mykart, fastshop, grocio, quickmart, etc.

✅ 2. Project Folder me Jaao

    cd my-ecommerce-app
        
✅ 3. Expo Dev Server Start Karo

    npx expo start

    NOTE:
    | Iske baad terminal me QR Code aayega → usko aap Expo Go se scan karke mobile me app chala sakte ho.

    ![WhatsApp Image 2025-11-14 at 22 55 28_27dca8b5](https://github.com/user-attachments/assets/7246f3af-848a-4638-a25e-88a5e1d8af78)

ADDITIONAL
⚙️ Important: Install Required Libraries
Aap ek scalable e-commerce app bana rahe ho, isliye essential libraries abhi install karna best hai.

1️⃣ React Navigation Setup

    npm install @react-navigation/native
    npm install @react-navigation/native-stack
    npm install @react-navigation/bottom-tabs

Expo ke navigation dependencies install karo:

        expo install react-native-screens react-native-safe-area-context

2️⃣ Redux Toolkit (state management)

    npm install @reduxjs/toolkit react-redux

3️⃣ Axios (API calling)

    npm install axios

4️⃣ Async Storage (local storage)

    expo install @react-native-async-storage/async-storage

5️⃣ Vector Icons (UI me zaroor lagenge)

    expo install react-native-vector-icons

6️⃣ React Native Reanimated (future animations ke liye)

    expo install react-native-reanimated

7️⃣ Gesture Handler (bottom sheet, swipes, etc.)

    expo install react-native-gesture-handler

🔥 BONUS: ESLint + Prettier (optional but recommended)

    npm install --save-dev eslint prettier

🎉 Setup Complete!
Aapka mobile app single-vendor → multi-vendor ready structure ke saath chalne ke liye prepared hai.
