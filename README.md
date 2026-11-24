<div align="center">

<img src="assets/banner.png" alt="NIMA — NISA + MAIA dalam satu aplikasi" width="100%" />

<br />

<img src="https://img.shields.io/github/v/release/KoRifCan/nima-releases?style=for-the-badge&amp;label=versi&amp;labelColor=2B1038&amp;color=7C3E99" alt="Versi terbaru" />
<img src="https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&amp;logo=android&amp;logoColor=white&amp;labelColor=2B1038" alt="Android 7.0 atau lebih baru" />
<img src="https://img.shields.io/badge/ARM64-arm64--v8a-9A57BC?style=for-the-badge&amp;labelColor=2B1038" alt="ARM64" />
<img src="https://img.shields.io/badge/SHA--256-tersedia-E9C46A?style=for-the-badge&amp;labelColor=2B1038" alt="Checksum SHA-256 tersedia" />

<br /><br />

<a href="https://github.com/KoRifCan/nima-releases/releases/latest">
  <img src="assets/btn-download.png" alt="Unduh APK terbaru" width="330" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/KoRifCan/nima-releases/releases">
  <img src="assets/btn-releases.png" alt="Lihat semua rilis" width="330" />
</a>

<br /><br />

**Aplikasi operasi lapangan untuk petugas MyRepublic.**<br />
<sub>NISA + MAIA dalam satu aplikasi · Tanpa akun GitHub · Tanpa iklan</sub>

</div>

<img src="assets/divider.png" width="100%" alt="" />

## Kerja lapangan, dalam satu genggaman

NIMA menyatukan alur **NISA** dan **MAIA** tanpa WebView. Tiket, FAT Loss,
peta, ekspor laporan, dan aktivitas operasional lainnya tersedia dalam satu
aplikasi Android native yang ringan dan cepat.

Halaman ini adalah **kanal unduhan resmi** NIMA. Yang dipublikasikan di sini
hanya berkas pemasangan dan pembaruan — tidak ada data pelanggan, kata sandi,
atau token.

<table>
<tr>
<td align="center" width="33%" valign="top">
<img src="assets/icons/update.png" width="46" alt="" /><br />
<b>Pembaruan di aplikasi</b><br />
<sub>Cek, unduh, dan pasang versi baru tanpa membuka browser.</sub>
</td>
<td align="center" width="33%" valign="top">
<img src="assets/icons/secure.png" width="46" alt="" /><br />
<b>Unduhan terverifikasi</b><br />
<sub>APK ditandatangani kunci rilis NIMA dan dilengkapi SHA-256.</sub>
</td>
<td align="center" width="33%" valign="top">
<img src="assets/icons/offline.png" width="46" alt="" /><br />
<b>Tetap produktif</b><br />
<sub>Antrean offline menyimpan pekerjaan saat sinyal terputus.</sub>
</td>
</tr>
<tr>
<td align="center" width="33%" valign="top">
<img src="assets/icons/map.png" width="46" alt="" /><br />
<b>Peta dan rute</b><br />
<sub>Lihat tiket di peta dan susun rute multi-titik.</sub>
</td>
<td align="center" width="33%" valign="top">
<img src="assets/icons/report.png" width="46" alt="" /><br />
<b>Laporan siap kirim</b><br />
<sub>Ekspor PDF dan CSV langsung dari perangkat.</sub>
</td>
<td align="center" width="33%" valign="top">
<img src="assets/icons/lock.png" width="46" alt="" /><br />
<b>Data tetap privat</b><br />
<sub>Kunci aplikasi, ID tersamarkan, dan sesi berbatas waktu.</sub>
</td>
</tr>
</table>

<img src="assets/divider.png" width="100%" alt="" />

## Sebelum memasang

| | |
|:--|:--|
| **Android** | 7.0 (API 24) atau lebih baru |
| **Arsitektur** | ARM64 (`arm64-v8a`) |
| **Ukuran unduhan** | sekitar 29 MB |
| **Akun** | NISA/MAIA yang aktif |

## Mulai dalam tiga langkah

| 1 | 2 | 3 |
|:--:|:--:|:--:|
| **Unduh**<br /><sub>Buka halaman rilis terbaru dan ambil berkas `.apk`.</sub> | **Pasang**<br /><sub>Izinkan “Instal aplikasi tak dikenal” bila diminta.</sub> | **Masuk**<br /><sub>Buka NIMA dan login dengan akun Anda.</sub> |

> [!IMPORTANT]
> Jika sebelumnya pernah memasang build uji **0.4.3 atau lebih lama**,
> hapus NIMA sekali, reboot ponsel, lalu pasang versi terbaru. Build lama
> memakai kunci tanda tangan berbeda. Setelah versi 0.5.0 atau lebih baru
> terpasang, pembaruan berikutnya tidak perlu menghapus aplikasi.

> [!NOTE]
> Aplikasi memerlukan koneksi internet untuk login dan sinkronisasi. Tidak
> perlu akun GitHub untuk mengunduh atau memperbarui NIMA.

<img src="assets/divider.png" width="100%" alt="" />

## Pembaruan tanpa ribet

Buka **Pengaturan → Pembaruan aplikasi** di NIMA:

- **Cek pembaruan** — memeriksa versi terbaru kapan saja.
- **Cek otomatis** — aktif secara default, paling sering sekali setiap 6 jam.
- **Ikuti pra-rilis (beta)** — mencoba versi lebih awal; nonaktif secara default.
- **Unduh & pasang** — mengunduh APK, memverifikasi SHA-256 bila tersedia,
  lalu membuka installer Android.

| Kanal | Status di GitHub | Terlihat di aplikasi |
|:--|:--|:--|
| **Stabil** | Rilis biasa | ✅ Semua pengguna |
| **Beta** | Ditandai *pre-release* | 🧪 Hanya bila kanal beta diaktifkan |
| **Draf** | Belum dipublikasikan | 🚫 Tidak pernah |

Rilis draf tidak pernah dikirim ke aplikasi, sehingga versi yang masih
disiapkan aman tersimpan tanpa terdeteksi. Pengguna kanal stabil tidak akan
terganggu oleh rilis beta.

<img src="assets/divider.png" width="100%" alt="" />

## Unduhan aman

Setiap rilis menyertakan berkas checksum
`nima-<versi>-arm64.apk.sha256`. Cocokkan sebelum memasang:

**Linux / macOS**

```bash
sha256sum -c nima-<versi>-arm64.apk.sha256
```

**Windows (PowerShell)**

```powershell
Get-FileHash .\nima-<versi>-arm64.apk -Algorithm SHA256
```

Bandingkan hasilnya dengan isi berkas `.sha256` di halaman rilis. Aplikasi
juga memverifikasi checksum secara otomatis bila aset tersebut tersedia.

<img src="assets/divider.png" width="100%" alt="" />

## Pertanyaan yang sering muncul

<details>
<summary><b>Apakah APK ini resmi?</b></summary>

Ya. APK diterbitkan oleh pembuat NIMA dan ditandatangani dengan kunci rilis
NIMA yang tetap, sehingga pembaruan dapat dipasang di atas versi sebelumnya.
Unduh hanya dari halaman rilis ini.

</details>

<details>
<summary><b>Mengapa Play Protect menampilkan peringatan?</b></summary>

APK ini dipasang di luar Play Store, sehingga Android dapat menampilkan
peringatan. Selama berkas berasal dari halaman rilis ini dan checksum-nya
cocok, berkas tersebut adalah berkas resmi NIMA.

</details>

<details>
<summary><b>Muncul “Aplikasi tidak terpasang”. Apa yang harus dilakukan?</b></summary>

Biasanya karena versi lama memakai kunci tanda tangan berbeda. Hapus NIMA
sekali, reboot ponsel, lalu pasang ulang. Data aplikasi akan hilang dan perlu
login ulang.

</details>

<details>
<summary><b>Versi beta tidak muncul.</b></summary>

Buka **Pengaturan → Pembaruan aplikasi**, lalu aktifkan
**Ikuti pra-rilis (beta)**. Setelah itu tekan **Cek pembaruan**.

</details>

<details>
<summary><b>Apakah data saya dikirim ke GitHub?</b></summary>

Tidak. GitHub hanya dipakai untuk membaca daftar rilis dan mengunduh APK.
Data operasional tetap dikirim ke layanan NISA/MAIA seperti biasa.

</details>

<details>
<summary><b>Apakah saya perlu akun GitHub?</b></summary>

Tidak. Aplikasi tidak meminta login GitHub dan tidak menyimpan token GitHub.

</details>

<details>
<summary><b>Di mana kode sumbernya?</b></summary>

Kode sumber disimpan di repositori privat. Repositori ini hanya berisi berkas
rilis yang boleh diunduh publik.

</details>

<details>
<summary><b>Bagaimana jika saya mengalami kendala?</b></summary>

Hubungi admin atau tim IT operasi Anda. Sertakan versi NIMA yang terpasang
(terlihat di **Pengaturan → Tentang NIMA**) dan pesan kesalahannya.

</details>

<img src="assets/divider.png" width="100%" alt="" />

## English

<details>
<summary><b>NIMA in English</b></summary>


NIMA is the Android field-operations app that brings NISA and MAIA workflows
together for MyRepublic field officers. Download the latest APK from the
[releases page](https://github.com/KoRifCan/nima-releases/releases/latest).

- Requires Android 7.0+, an ARM64 device, and an active NISA/MAIA account.
- Updates are delivered inside the app (**Settings → App updates**), with an
  optional beta channel and automatic checks every six hours at most.
- Draft releases are never offered. Stable users only see stable releases.
- No GitHub account or token is required. Verify the download with the
  published SHA-256 checksum.

</details>

<img src="assets/divider.png" width="100%" alt="" />

<div align="center">
<sub>Dibuat oleh <b>KoRifCan</b> · NIMA · Android ARM64</sub><br />
<sub>Kode sumber privat · Hanya berkas rilis yang dipublikasikan di sini.</sub>
</div>
