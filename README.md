# NIMA

**NIMA** adalah aplikasi Android untuk operasi lapangan yang menyatukan
pekerjaan **NISA** dan **MAIA** dalam satu aplikasi. Dibuat oleh **KoRifCan**.

Halaman ini adalah tempat unduhan resmi APK NIMA. Yang tersedia di sini hanya
berkas pemasangan dan pembaruan — tidak ada data pelanggan, kata sandi, atau
token di repositori ini.

## Unduh versi terbaru

**[⬇️ Buka halaman rilis terbaru](https://github.com/KoRifCan/nima-releases/releases/latest)**

Setiap rilis menyertakan:

| Berkas | Keterangan |
|---|---|
| `nima-<versi>-arm64.apk` | Aplikasi untuk Android ARM64 |
| `nima-<versi>-arm64.apk.sha256` | Checksum untuk memeriksa unduhan |

## Sebelum memasang

- Android **7.0 (API 24)** atau lebih baru.
- Perangkat **ARM64** (mayoritas ponsel Android modern).
- Akun NISA/MAIA yang aktif — aplikasi memerlukan login untuk digunakan.
- Ruang penyimpanan sekitar **30 MB**.

## Cara memasang

1. Buka halaman rilis, lalu unduh berkas `.apk` terbaru.
2. Buka berkas tersebut dari notifikasi atau aplikasi **Files**.
3. Jika Android meminta izin, aktifkan **Instal aplikasi tak dikenal** untuk
   aplikasi yang membuka berkas (Files/Chrome), lalu lanjutkan.
4. Tunggu sampai pemasangan selesai, lalu buka **NIMA** dan login.

Jika sebelumnya pernah memasang build uji **0.4.3 atau lebih lama**, hapus
NIMA sekali, reboot ponsel, lalu pasang versi ini. Setelah versi 0.5.0
terpasang, pembaruan berikutnya dapat dipasang langsung tanpa menghapus
aplikasi atau kehilangan data.

## Pembaruan di dalam aplikasi

Buka **Pengaturan → Pembaruan aplikasi**. Di sana tersedia:

- **Cek pembaruan** — memeriksa versi terbaru secara manual.
- **Cek pembaruan otomatis** — aktif secara default, paling sering sekali
  setiap 6 jam.
- **Ikuti pra-rilis (beta)** — menampilkan versi beta bagi yang ingin mencoba
  lebih awal. Nonaktif secara default.
- **Unduh & pasang** — mengunduh APK dari halaman rilis, memverifikasi
  SHA-256 bila tersedia, lalu membuka installer Android.

Tiga status rilis di GitHub:

| Status | Terlihat di aplikasi |
|---|---|
| Rilis biasa (stabil) | Semua pengguna |
| Pre-release (beta) | Hanya jika kanal beta diaktifkan |
| Draf | Tidak pernah terlihat |

Aplikasi tidak memerlukan akun GitHub dan tidak menyimpan token GitHub.
Pemeriksaan pembaruan hanya membaca informasi rilis publik.

## Verifikasi unduhan

Checksum juga tercantum sebagai aset `.sha256` pada setiap rilis.

**Linux / macOS**

```bash
sha256sum -c nima-<versi>-arm64.apk.sha256
```

**Windows (PowerShell)**

```powershell
Get-FileHash .\nima-<versi>-arm64.apk -Algorithm SHA256
```

Bandingkan hasilnya dengan isi berkas `.sha256` di halaman rilis.

## Pertanyaan yang sering muncul

**Apakah APK ini resmi?**
Ya. APK diterbitkan oleh pembuat NIMA dan ditandatangani dengan kunci rilis
NIMA yang tetap, sehingga pembaruan dapat dipasang di atas versi sebelumnya.

**Mengapa Play Protect menampilkan peringatan?**
APK ini dipasang di luar Play Store. Selama berkas diunduh dari halaman rilis
ini dan checksum-nya cocok, berkas tersebut adalah berkas resmi NIMA.

**Muncul "Aplikasi tidak terpasang".**
Biasanya karena versi lama memakai kunci tanda tangan berbeda. Hapus NIMA
sekali, reboot, lalu pasang ulang. Data aplikasi akan hilang dan perlu login
ulang.

**Versi beta tidak muncul.**
Buka **Pengaturan → Pembaruan aplikasi**, lalu aktifkan
**Ikuti pra-rilis (beta)**. Pengguna kanal stabil tidak akan terganggu oleh
versi beta.

**Apakah data saya dikirim ke GitHub?**
Tidak. GitHub hanya dipakai untuk membaca daftar rilis dan mengunduh APK.
Data operasional tetap dikirim ke layanan NISA/MAIA seperti biasa.

**Apakah saya perlu akun GitHub?**
Tidak.

**Di mana kode sumbernya?**
Kode sumber disimpan di repositori privat. Repositori ini hanya berisi berkas
rilis yang boleh diunduh publik.

## Riwayat versi

Lihat [halaman Releases](https://github.com/KoRifCan/nima-releases/releases)
untuk daftar versi dan catatan perubahan.

---

## English

NIMA is the Android field-operations app that brings NISA and MAIA workflows
together. Download the latest APK from the
[releases page](https://github.com/KoRifCan/nima-releases/releases/latest).

Requirements: Android 7.0+, ARM64 device, and an active NISA/MAIA account.
Updates are delivered inside the app (**Settings → App updates**), including
an optional beta channel. Draft releases are never offered. No GitHub account
or token is required. Verify your download with the published SHA-256
checksum.

---

Pembuat: **KoRifCan**
