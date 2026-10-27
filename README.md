# ceknricek

Database domain publik yang diperbarui otomatis setelah snapshot terbaru selesai diunduh dan diverifikasi checksum.

## File

- `domains_isp.zip` — snapshot terbaru; isi file bernama `domains_isp`.
- `metadata.json` — versi, waktu WIB, ukuran, jumlah domain, dan SHA-256.
- `added.txt` — domain baru dibanding snapshot sebelumnya.
- `removed.txt` — domain yang hilang dibanding snapshot sebelumnya.
- `count-trust.txt` — jumlah domain unik.

## Versi terbaru

- Diperbarui: `2026-11-28 21-05-13 WIB`
- Jumlah domain: `10,292,232`
- SHA-256 raw: `c76743a5ad5d11e4d67e972f610e8d4632b6824e1de4faff82fd8fdb402322d6`

## Penggunaan

```bash
wget -q https://github.com/kopikoganteng07-del/ceknricek/raw/main/domains_isp.zip
unzip -p domains_isp.zip domains_isp | grep -Fxi 'example.com'
```

Repository ini menyediakan salinan data untuk kebutuhan pengecekan teknis.
