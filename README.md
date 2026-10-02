# AM App Landing Page

## Struktur GitHub yang disarankan

```text
repository/
├── index.html
└── app-release.apk
```

Website menggunakan `./app-release.apk` sebagai link download.

### Ganti link GitHub

Buka `index.html`, lalu ubah:

```js
const GITHUB_URL = "https://github.com/USERNAME/REPOSITORY";
```

menjadi URL repository kamu.

## GitHub Pages

1. Upload `index.html` dan `app-release.apk` ke repository.
2. Buka **Settings → Pages**.
3. Pilih branch yang berisi `index.html` dan folder `/ (root)`.
4. Save.
5. Gunakan URL GitHub Pages yang diberikan GitHub.

Catatan: untuk APK yang besar, GitHub Releases lebih cocok daripada menyimpan binary besar langsung di repository.
