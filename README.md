TG NPDCL DIGITAL DIARY 2027–2041 — ప్రాజెక్ట్ ఫైళ్లు

1) వెబ్ యాప్:
   web/index.html, manifest.webmanifest, service-worker.js, icon.svg
   Android Chromeలో Installable PWA కావాలంటే ఈ ఫైళ్లను HTTPS ఉన్న వెబ్ హోస్టింగ్‌లో ఉంచాలి. HTML ఫైల్‌ను నేరుగా తెరిస్తే Service Worker/offline install అందుబాటు ఉండకపోవచ్చు.

2) Android Studio ప్రాజెక్ట్:
   android/ ఫోల్డర్‌ను Android Studioలో Open చేయండి. Gradle sync పూర్తి చేసి Build > Build APK(s) ఎంచుకోండి.
   రూపొందిన APK సాధారణంగా android/app/build/outputs/apk/debug/app-debug.apk వద్ద ఉంటుంది.

గమనికలు:
- ఈ ZIPలో compile చేసిన APK లేదు; Android Studio ద్వారా build చేయాల్సిన source project ఉంది.
- డైరీ డేటా local browser storageలో ఉంటుంది. ఫోన్/బ్రౌజర్ డేటా క్లియర్ అయితే పోవచ్చు; క్రమం తప్పకుండా JSON బ్యాకప్ తీసుకోండి.
- PIN lock సాధారణ PIN గేట్ మాత్రమే, encryption కాదు.
- వాయిస్ టైపింగ్‌కు Android Chrome SpeechRecognition మద్దతు అవసరం. ఆడియో రికార్డింగ్‌కు microphone permission అవసరం.
- ముఖచిత్రంలోని అంబేద్కర్ చిత్రం ప్రస్తుతం శైలీకృత illustration; అధికారిక TG NPDCL లోగో placeholder మాత్రమే.
- 2027–2041 సెలవులు/పండుగలు అధికారికంగా ధృవీకరించిన పూర్తి జాబితాగా ఇందులో ముందే నింపబడలేదు; Holidays ట్యాబ్‌లో చేర్చాలి.
