# ceknricek

Database domain publik yang diperbarui otomatis setelah snapshot terbaru selesai diunduh dan diverifikasi checksum.

## File

- `domains_isp.zip` — snapshot terbaru; isi file bernama `domains_isp`.
- `metadata.json` — versi, waktu WIB, ukuran, jumlah domain, dan SHA-256.
- `added.txt` — domain baru dibanding snapshot sebelumnya.
- `removed.txt` — domain yang hilang dibanding snapshot sebelumnya.
- `count-trust.txt` — jumlah domain unik.

## Versi terbaru

- Diperbarui: `2026-11-07 19-44-54 WIB`
- Jumlah domain: `10,067,819`
- SHA-256 raw: `8a4cd69e8dc46f04a37eac9556134d0425fd2ddf46a2f959c62d4146bc916b29`

## Penggunaan

```bash
wget -q https://github.com/kopikoganteng07-del/ceknricek/raw/main/domains_isp.zip
unzip -p domains_isp.zip domains_isp | grep -Fxi 'example.com'
```

Repository ini menyediakan salinan data untuk kebutuhan pengecekan teknis.
