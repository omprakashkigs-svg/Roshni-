# ROSHNI AI – Android Starter (v0.1.0)

यह एक शुरुआती native Android project scaffold है, पूर्ण Jarvis नहीं।

## क्या काम करता है
- Hindi speech recognition (बटन दबाकर)
- Hindi Text-to-Speech (डिवाइस में Hindi TTS engine उपलब्ध होने पर)
- WhatsApp / Instagram / Facebook / YouTube खोलने के basic commands
- Persistent foreground notification service का starter

## क्या अभी नहीं बना है
- Always-on wake word
- Owner voice biometric verification
- WhatsApp/Instagram के अंदर संदेश पढ़ना/भेजना
- Incoming call assistant
- AI cloud brain / API integration
- Photo/video editing
- Intrusion detection / account compromise detection
- Long-term encrypted memory

## Build करने के लिए
1. Android Studio का वर्तमान stable संस्करण इंस्टॉल करें।
2. इस ZIP को extract करें।
3. Android Studio में `ROSHNI_AI_Android_Starter` folder खोलें।
4. SDK Platform 36 और JDK 17 सेट करें।
5. Gradle Sync करें।
6. Android फोन में Developer Options और USB debugging सक्षम करें।
7. फोन जोड़कर Run दबाएँ।
8. Microphone और notification permissions दें।

## सुरक्षा
- API key को source code में hardcode न करें।
- Microphone service को केवल स्पष्ट user action और permission के बाद शुरू करें।
- Android lock screen को bypass न करें।
- Voice match अकेले high-risk actions की सुरक्षा के लिए पर्याप्त नहीं है।
- संदेश भेजने, कॉल करने, भुगतान, और account changes से पहले confirmation रखें।

## अगला विकास चरण
पहले इस scaffold को Android Studio में build और device पर test करें। इसके बाद अलग modules में AI backend, secure memory, notification access, owner verification और supported messaging integrations जोड़े जाएँगे।
