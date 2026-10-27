# ceknricek

Database domain publik yang diperbarui otomatis setelah snapshot terbaru selesai diunduh dan diverifikasi checksum.

## File

- `domains_isp.zip` — snapshot terbaru; isi file bernama `domains_isp`.
- `metadata.json` — versi, waktu WIB, ukuran, jumlah domain, dan SHA-256.
- `added.txt` — domain baru dibanding snapshot sebelumnya.
- `removed.txt` — domain yang hilang dibanding snapshot sebelumnya.
- `count-trust.txt` — jumlah domain unik.

## Versi terbaru

- Diperbarui: `2026-10-31 18-55-37 WIB`
- Jumlah domain: `9,993,811`
- SHA-256 raw: `1f5d9fc27fc8ae5ae78726793436b5f4514e71ca4a0e10a3196b3685c4c2581e`

## Penggunaan

```bash
wget -q https://github.com/kopikoganteng07-del/ceknricek/raw/main/domains_isp.zip
unzip -p domains_isp.zip domains_isp | grep -Fxi 'example.com'
```

Repository ini menyediakan salinan data untuk kebutuhan pengecekan teknis.
