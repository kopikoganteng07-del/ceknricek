# ceknricek

Database domain publik yang diperbarui otomatis setelah snapshot terbaru selesai diunduh dan diverifikasi checksum.

## File

- `domains_isp.zip` — snapshot terbaru; isi file bernama `domains_isp`.
- `metadata.json` — versi, waktu WIB, ukuran, jumlah domain, dan SHA-256.
- `added.txt` — domain baru dibanding snapshot sebelumnya.
- `removed.txt` — domain yang hilang dibanding snapshot sebelumnya.
- `count-trust.txt` — jumlah domain unik.

## Versi terbaru

- Diperbarui: `2026-11-14 17-45-46 WIB`
- Jumlah domain: `10,128,912`
- SHA-256 raw: `80a97437ef3381c1045bdc2962b5f704aa36c1695c04256b023e9c0f1ae5c4e0`

## Penggunaan

```bash
wget -q https://github.com/kopikoganteng07-del/ceknricek/raw/main/domains_isp.zip
unzip -p domains_isp.zip domains_isp | grep -Fxi 'example.com'
```

Repository ini menyediakan salinan data untuk kebutuhan pengecekan teknis.
