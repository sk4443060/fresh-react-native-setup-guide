Jab main expo install react-native-screens react-native-safe-area-context install kar raha hun tab mujhe ye error de raha hai:

'expo' is not recognized as an internal or external command,
operable program or batch file.

Waise is package ka kaam kya hai? Kya ise install karna jaroori hai?
------------------------------------------------------------------------
Ye error common hai — solution simple hai.
Neeche explanation + fix dono de raha hoon.
------------------------------------------------------------------------

❌ Error: 'expo' is not recognized as an internal or external command
Reason:
  Aapke system me Expo CLI globally install nahi hai.
  Isliye jab aap expo install ... run karte ho, Windows us command ko nahi pahchaan pata.

  ✅ Solution (2 Options)
  OPTION 1 — Use npx expo install (Recommended)
  Aapko Expo CLI globally install karne ki zaroorat nahi.
  Bas ye command likho:

    npx expo install react-native-screens react-native-safe-area-context

  ✔ Error solve
  ✔ Safe
  ✔ Expo’s recommended way

  OPTION 2 — Install Expo CLI globally (Optional)
  Agar aap direct expo install use karna chahte ho:

    npm install -g expo-cli

  Install ke baad:

    expo install react-native-screens react-native-safe-area-context

⭐ Ye packages ka kaam kya hai? (Simple Explanation)
1. react-native-screens
App ke different screens ko native level pe optimize karta hai.
Benefits:
- App smooth lagta hai
- Navigation transitions fast
- Memory usage kam
👉 Navigation chalane ke liye highly recommended.

2. react-native-safe-area-context
Different devices me notch, cutouts, dynamic islands, rounded corners hote hain.
Ye package ensure karta hai ki UI:
- notch ke andar na jaye
- iPhone ke top edges me cut na ho
- Android statusbar se overlap na ho
👉 Modern phones par safe layout maintain karta hai.
👉 Navigation + layout ke liye zaroori hai.

🎯 Kya ye dono install karna jaroori hai?
✔ Yes, agar aap React Navigation use kar rahe ho
E Commerce app me navigation toh hoga hi.
Without them → Navigation errors, layout issues, crashes.

🔍 AAPKA NEXT STEP:
Run karein:

    npx expo install react-native-screens react-native-safe-area-context

Done. No more errors.
