# 🎨 Internal CSS & External CSS pada HTML

## 📌 Apa itu CSS?
CSS (*Cascading Style Sheets*) adalah bahasa untuk mengatur tampilan halaman HTML seperti warna, teks, layout, dan desain visual lainnya. Dalam HTML, terdapat beberapa cara menambahkan CSS, dua di antaranya adalah **Internal CSS** dan **External CSS**.

---

## 🎯 Perbedaan Internal CSS dan External CSS

| Aspek Perbandingan | **Internal CSS** | **External CSS** |
|-------------------|------------------|------------------|
| Lokasi CSS | Di dalam tag `<style>` pada `<head>` | Di file `.css` terpisah |
| Struktur Kode | Kurang rapi | Lebih rapi |
| Skalabilitas | Kurang bagus untuk banyak halaman | Sangat bagus untuk website besar |
| Profesionalitas | Standar | Lebih profesional |
| Kecepatan Editing | Cepat untuk 1 halaman | Lebih enak jika project besar |
| Cocok Untuk | Halaman kecil / 1 file | Banyak halaman / project besar |

---

## 🎯 Penjelasan Singkat
- **Internal CSS** → CSS ditulis langsung di dalam file HTML. Cocok untuk project kecil.
- **External CSS** → CSS ditulis di file `.css` terpisah, HTML hanya memanggilnya. Cocok untuk project besar karena rapi dan terstruktur.

---

## ✅ Contoh Kode HTML (Internal + External dalam 1 Halaman)

```html
<!DOCTYPE html>
<html>
<head>
    <!-- INTERNAL CSS -->
    <style>
        p {
            color: blue;
            text-align: center;
        }
    </style>

    <!-- EXTERNAL CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2>Contoh Internal CSS</h2>
    <p>Ini adalah paragraf dengan Internal CSS</p>

    <h2>Contoh External CSS</h2>
    <p class="text">Ini adalah paragraf dengan External CSS</p>
</body>
</html>
