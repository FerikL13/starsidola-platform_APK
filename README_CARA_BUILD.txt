STARS IDOLA - ZIP Builder

Isi repo ini:
1. source-apk.zip
2. .github/workflows/build-apk.yml

Cara pakai:
1. Buat repo GitHub baru.
2. Upload isi folder ini ke repo.
3. Buka tab Actions.
4. Jalankan workflow "Build STARS IDOLA APK from ZIP".
5. Setelah selesai, download artifact: STARS_IDOLA_APK_DEBUG.

Catatan:
- GitHub tidak bisa build langsung kalau hanya upload source-apk.zip tanpa workflow.
- Workflow ini yang extract source-apk.zip lalu build APK.
