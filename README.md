# Sarvatobhadra Vedic Transit — Android APK

यह project मौजूदा `index.html` को Android WebView app में पैक करता है।

## GitHub से APK बनाने का तरीका

1. इस पूरे folder को GitHub repository में upload करें।
2. GitHub में **Actions** खोलें।
3. `Build Android APK` workflow चलाएँ, या `main/master` पर push करें।
4. Workflow पूरा होने पर **Artifacts** में `sarvatobhadra-debug-apk` मिलेगा।
5. ZIP artifact डाउनलोड करके उसमें से `app-debug.apk` फोन में install करें।

## App में
- Live Swiss Ephemeris API के लिए Internet permission
- GPS/Browser geolocation के लिए Android location permission
- मौजूदा place autocomplete और transit HTML उसी रूप में रखा गया है।

ध्यान दें: APK का calculation data external Swiss Ephemeris API और Nominatim services से आता है; Android app में HTML embedded है, इसलिए GitHub Pages की जरूरत APK चलाने के लिए नहीं है।
