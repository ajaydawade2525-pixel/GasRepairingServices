Gas Repairing Services — Android Studio Project

इस फ़ोल्डर में Android WebView ऐप का शुरुआती प्रोजेक्ट है।

बनाने का तरीका:
1. कंप्यूटर पर Android Studio इंस्टॉल करें।
2. Android Studio में इस फ़ोल्डर (GasRepairingAndroid) को Open करें।
3. Gradle sync पूरा होने दें और आवश्यक Android SDK डाउनलोड करें।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
5. APK आम तौर पर app/build/outputs/apk/debug/app-debug.apk में मिलेगा।

महत्वपूर्ण सीमाएँ:
- यह APK-ready starter project है, पहले से बना हुआ APK नहीं।
- मौजूदा डेमो बुकिंग उसी डिवाइस के browser/WebView storage में सेव होती है; ग्राहक और मालिक के अलग-अलग मोबाइलों के बीच ऑनलाइन सिंक नहीं है।
- Admin credentials demo-only हैं (admin / 1234); इन्हें वास्तविक उपयोग में सुरक्षित नहीं माना जा सकता।
- WhatsApp बटन WhatsApp खोलता है; बैकग्राउंड नोटिफिकेशन, साझा डेटाबेस और सुरक्षित लॉगिन के लिए backend/Firebase तथा अतिरिक्त सेटअप चाहिए।
