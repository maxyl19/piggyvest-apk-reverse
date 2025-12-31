# PiggyVest v5.4.6 APK Reverse Engineering

## 🎯 What I Accomplished
- ✅ Decompiled 45k+ smali files (5 dex classes)
- ✅ Extracted LIVE production API + 4 secret keys  
- ✅ Discovered client-side password encryption
- ✅ Mapped auth flow in Termux only
## 🔑 LIVE SECRETS EXTRACTED
API: https://api.piggyvest.com/v5
Android API Key: sS0xbXxkiNokI6zWQdEF2mTIP6NsikO465ORtignZmEOuoLNp3j7eRrTszBwniud
FCM Key: AIzaSyBjNDIOmkCxtBPvozqbHnudg40SvFcl2lI
LOGIN_ENCRYPTION_KEY: f069d261-9fe9-48d7-b603-044e4d1f3945
## 🛠️ Termux Workflow
APK bundle → base.apk → apktool 2.9.3 → 45k smali → curl API tests
undefined
