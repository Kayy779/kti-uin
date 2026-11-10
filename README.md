# KTI UIN — Skill OpenCode

Skill [OpenCode](https://opencode.ai) untuk menulis Karya Tulis Ilmiah (skripsi, tesis, disertasi, proposal, makalah) mengikuti **Pedoman Penulisan KTI LPM UIN Palu Edisi Revisi 2020**.

Referensi menggunakan **Turabian System** dengan catatan kaki (footnote) — bukan APA/IEEE.

## Fitur

- Struktur bab proposal & skripsi lengkap (penelitian pustaka & lapangan: kuantitatif, kualitatif, PTK, pengembangan)
- Ketentuan format fisik: font, margin, spasi exactly, penomoran halaman, sampul, dsb.
- Aturan catatan kaki Turabian (`Ibid.`, `idem`, transliterasi, dsb.)
- Aturan daftar pustaka (urut abjad, nama dibalik, indent 1,25 cm)
- Transliterasi Arab-Latin sistem Library of Congress (LC)
- Checklist verifikasi sebelum menyatakan selesai
- Daftar anti-pola (kesalahan umum yang harus dihindari)

## Instalasi

### Windows (PowerShell)

```powershell
git clone https://github.com/<USERNAME>/kti-uin.git "$env:USERPROFILE\.config\opencode\skill\kti-uin"
```

### Linux / macOS

```bash
git clone https://github.com/<USERNAME>/kti-uin.git ~/.config/opencode/skill/kti-uin
```

Ganti `<USERNAME>` dengan username GitHub Anda.

Setelah clone, jalankan ulang OpenCode — skill `kti-uin` akan otomatis terdeteksi dan bisa dipanggil:

```
@kti-uin tuliskan latar belakang skripsi saya
```

### Update

```bash
cd ~/.config/opencode/skill/kti-uin && git pull
```

## Cara Pakai

Skill ini otomatis relevan ketika Anda meminta OpenCode untuk:

- Menulis / merevisi proposal penelitian, skripsi, tesis, atau makalah
- Memeriksa format & sitasi sesuai pedoman UIN Palu
- Membuat kerangka (outline) BAB I–V
- Memformat catatan kaki dan daftar pustaka Turabian
- Melakukan transliterasi Arab-Latin

## Struktur Repo

```
├── SKILL.md      # File skill utama (frontmatter + pedoman lengkap)
├── README.md
├── LICENSE
└── .gitignore
```

## Sumber

Pedoman Penulisan Karya Tulis Ilmiah Skripsi, Tesis dan Disertasi (Edisi Revisi), Lembaga Penjaminan Mutu (LPM) UIN Palu, 2020.

## Lisensi

MIT — lihat [LICENSE](LICENSE).
