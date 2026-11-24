# NIMA Releases

Repositori publik untuk APK dan metadata pembaruan **NIMA — NISA + MAIA**.
Kode sumber disimpan privat di [`KoRifCan/NIMA`](https://github.com/KoRifCan/NIMA).

## Unduh

Buka halaman **Releases** dan unduh aset terbaru:

```text
nima-<versi>-arm64.apk
nima-<versi>-arm64.apk.sha256
```

APK hanya untuk perangkat **Android ARM64** (arm64-v8a), `minSdk 24`.

## Kanal rilis

| Kanal | GitHub Release | Terdeteksi di app |
|---|---|---|
| **Stabil** | Rilis biasa | Semua pengguna |
| **Beta / pra-rilis** | Ditandai **Pre-release** | Hanya bila **Ikuti pra-rilis (beta)** aktif |
| **Draf** | Belum dipublikasikan | Tidak pernah |

Aplikasi memeriksa rilis lewat GitHub API tanpa token. Rilis draf tidak
pernah muncul, dan rilis pra-rilis hanya ditawarkan setelah pengguna
mengaktifkan kanal beta di **Pengaturan → Pembaruan**.

## Verifikasi manual

```bash
sha256sum -c nima-<versi>-arm64.apk.sha256
```

Checksum juga ditampilkan di halaman rilis. Aplikasi memverifikasi SHA-256
sebelum menyerahkan APK ke installer Android bila aset `.sha256` tersedia.

## Catatan pemasangan

- APK ditandatangani dengan release key NIMA yang stabil. Update berikutnya
  dapat dipasang di atas versi lama tanpa menghapus data.
- Build 0.5.0 adalah rilis pertama dengan release key baru. Bila perangkat
  masih memakai build debug 0.4.3 atau lebih lama, hapus NIMA sekali,
  reboot, lalu pasang 0.5.0.
- Jika Android menolak instalasi, izinkan **NIMA** memasang aplikasi dari
  **Pengaturan → Aplikasi → NIMA → Instal aplikasi tak dikenal**.
