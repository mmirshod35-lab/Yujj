# Savol-Javob Android APK

Bu loyiha HTML/CSS/JavaScript oynasini Android WebView ichida ochadi.

## GitHub orqali APK yig‘ish (telefon orqali ham mumkin)

1. Ushbu ZIP faylni telefonga yuklab oling va arxivni **Extract / Chiqarish** qiling.
2. GitHub’da `SavolJavob` nomli repository yarating.
3. Repository ichida **Add file → Upload files** ni bosing.
4. ZIP ichidagi fayl va papkalarni (ZIP faylining o‘zini emas) yuklang. `.github` yashirin papkasi ham yuklanganiga ishonch hosil qiling.
5. **Commit changes** bosing.
6. Repository → **Actions** ga kiring. `Build Savol-Javob APK` ishga tushadi.
7. Yashil muvaffaqiyatli build tugagach, ishga tushgan workflow sahifasini oching.
8. Pastdagi **Artifacts** bo‘limidan `SavolJavob-APK` ni yuklab oling.
9. Yuklangan artifact ZIP ichida `app-debug.apk` bo‘ladi. Uni chiqarib, APK faylni oching.

## Eslatma

- Har safar kodni o‘zgartirib `main` yoki `master` ga commit qilsangiz, build qayta ishga tushadi.
- Bu debug APK. Faqat o‘zingiz sinash uchun. Play Store uchun alohida release/signing sozlamalari kerak.
- Hozircha savol-javoblar ilova yopilganda saqlanib qolmaydi.
