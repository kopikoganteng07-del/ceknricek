# ceknricek

Database domain publik yang diperbarui otomatis setelah snapshot terbaru selesai diunduh dan diverifikasi checksum.

## File

- `domains_isp.zip` — snapshot terbaru; isi file bernama `domains_isp`.
- `metadata.json` — versi, waktu WIB, ukuran, jumlah domain, dan SHA-256.
- `added.txt` — domain baru dibanding snapshot sebelumnya.
- `removed.txt` — domain yang hilang dibanding snapshot sebelumnya.
- `count-trust.txt` — jumlah domain unik.

## Versi terbaru

- Diperbarui: `2026-11-21 16-15-28 WIB`
- Jumlah domain: `10,204,196`
- SHA-256 raw: `2526a6daa9f714c13b21d8b71aae36976f5b5d84d43eafbcbf1999340ef83427`

## Penggunaan

```bash
wget -q https://github.com/kopikoganteng07-del/ceknricek/raw/main/domains_isp.zip
unzip -p domains_isp.zip domains_isp | grep -Fxi 'example.com'
```

Repository ini menyediakan salinan data untuk kebutuhan pengecekan teknis.
