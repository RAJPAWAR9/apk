BOOSTER OS - APK BANANE KA TARIKA (phone se bhi ho jaata hai)

1) github.com par free account banao, naya repository banao (naam: booster-os).
2) Is zip ke andar ke SAARE files/folders (www, .github, package.json,
   capacitor.config.json, .gitignore) repository me upload karo.
   Dhyan: ".github" folder bhi upload hona chahiye.
3) Repository me "Actions" tab kholo -> "Build APK" -> "Run workflow".
4) 5-8 minute baad run complete hoga. Run kholo, neeche "Artifacts" me
   "BoosterOS-apk" download karo (zip hoga), uske andar app-debug.apk hai.
5) APK phone me install karo (Unknown sources allow karna padega).

Aage HTML badalni ho to sirf www/index.html replace karke dobara Run workflow.
Ye debug APK hai: install ho jaata hai, par Play Store ke liye signed release build alag banta hai.
