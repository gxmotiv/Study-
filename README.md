# NIOS Economics Study Centre

Mobile-first, offline-first NIOS Senior Secondary Economics (318) study helper.

## Android 32-bit APK
GitHub Actions builds a debug APK restricted to ARMv7 (`armeabi-v7a`). Open **Actions → Build Android 32-bit APK → latest successful run → Artifacts** to download it. The debug APK is directly installable on compatible Android devices.

## FreeModel AI
The app loads models dynamically from `https://freemodel.in/v1/models` and calls `/v1/chat/completions`. Enter your own key inside the app. It stays in temporary page memory and is never saved to localStorage or committed. Direct browser calls may be blocked by CORS. If free quota is exhausted, wait for reset; the app does not top up or enable paid usage.

## Privacy
No account, analytics or crash SDK. Notes, quiz score and progress are stored locally. AI requires internet; core study tools are offline-first. Some chapter entries are navigation-only because complete source notes were not available; verify content against official NIOS material.
