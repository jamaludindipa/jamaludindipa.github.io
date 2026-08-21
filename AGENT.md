# AGENT.md

## Portfolio Site Scope
- Repository ini adalah GitHub Pages portfolio statis untuk `jamaludindipa.github.io`.
- Fokus utama perubahan ada pada `index.html`, folder `projects/`, dan aset di `projectimg/`.

## Asset Rules
- Screenshot per project boleh dikompres resolusi dan ukuran file untuk optimasi loading halaman.
- Screenshot project sebaiknya disimpan dalam format web-friendly seperti `webp` bila memungkinkan.
- Hasil generate image untuk ilustrasi, diagram migrasi, atau visual buatan AI tidak perlu dikompres resolusinya secara agresif.
- Untuk image hasil generate, pertahankan resolusi yang layak presentasi; optimasi ukuran file boleh dilakukan selama kualitas visual tetap tinggi.
- Jangan menerapkan aturan kompres screenshot project ke ilustrasi hero, diagram migrasi, atau image presentational hasil generate.

## HRMS-HRIS Specific Rule
- Ilustrasi migrasi absensi seperti transisi `handkey -> fingerprint/face/palm scan` diperlakukan sebagai generated presentation asset, bukan screenshot project.
- Asset generated seperti `hrms-hris-migration-illustration.webp` harus dijaga kualitas visualnya karena berfungsi menjelaskan transformasi sistem.

## Editing Guidance
- Saat menambah project baru, pastikan ada:
  - card di homepage
  - detail page di `projects/`
  - integrasi screenshot/gallery bila relevan
- Jaga tone portfolio tetap profesional, singkat, dan berorientasi dampak operasional.
- Hindari memasukkan data sensitif, kredensial, endpoint internal, atau informasi perusahaan yang tidak disanitasi.

## Git Hygiene
- Jangan commit file backup lokal, asset sumber sementara, atau file generated yang tidak dipakai halaman.
- Jika tersedia dua versi asset (`png` source dan `webp` final), hanya commit versi final yang benar-benar dipakai halaman, kecuali user meminta sebaliknya.
