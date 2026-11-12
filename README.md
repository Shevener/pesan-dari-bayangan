# Analisis File

## Ekstrak metadata gambar

Jalankan ExifTool:

```bash
exiftool quest02.jpg
```

Hasil penting:

- Author/Artist: `Phantom_Admin`
- Koordinat GPS: `8° 12′ 41.98″ S, 114° 22′ 0.75″ E`
- XP Title: `Storika Coffee`

## Decode pesan

Isi `command.txt` berupa teks Base64. Decode dengan:

```bash
base64 --decode command.txt
```

Plaintext:

> Tanam malware di server utama besok jam 12 malam.
