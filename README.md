# 🌦 Tugas Akhir Praktikum Pemrograman Web 6- Weather Dashboard

Weather Dashboard adalah aplikasi web untuk menampilkan informasi cuaca real-time dan ramalan 5 hari berdasarkan lokasi yang dicari pengguna. Aplikasi ini dibangun tanpa framework, menggunakan **HTML, CSS, dan JavaScript murni**, serta memanfaatkan layanan **Open-Meteo API** dan **Nominatim (OpenStreetMap)** untuk data cuaca dan geocoding.

---

## ✨ Fitur Utama

| Fitur                   | Deskripsi                                                         |
| ----------------------- | ----------------------------------------------------------------- |
| 🌍 Pencarian Lokasi     | Cari kota dengan input + autocomplete.                            |
| 📍 Geocoding            | Mengubah nama kota menjadi koordinat otomatis.                    |
| ☀ Current Weather       | Temperatur, humidity, wind speed, ikon cuaca, lokasi & timestamp. |
| 📆 Forecast 5 Hari      | Temperatur min/max + ikon + deskripsi.                            |
| ♻ Auto Refresh          | Update otomatis setiap **5 menit**.                               |
| 🔄 Refresh Manual       | Tombol update instan.                                             |
| ❤️ Favorite City        | Simpan & hapus favorit (localStorage).                            |
| 🌗 Dark/Light Mode      | Tema dapat diganti kapan saja.                                    |
| 🌡 Celsius ↔ Fahrenheit | Konversi suhu real-time.                                          |
| ⏳ Loading Indicator     | Spinner ketika fetching API.                                      |
| 🛡 Error Handling       | Notifikasi saat request gagal/tidak ditemukan.                    |

---

## 🛠 Teknologi & Tools

* **HTML + CSS + JavaScript (Vanilla)**
* **Open-Meteo Weather API** *(tanpa API key)*
* **Nominatim OpenStreetMap Geocode** *(tanpa API key)*
* LocalStorage
* Client-Side Only

---

## 📦 Cara Menjalankan

```bash
git clone https://github.com/username/weather-dashboard.git
cd weather-dashboard
```

Untuk menjalankan:

> Klik `index.html` langsung, atau gunakan web server lokal jika terjadi CORS

```bash
python -m http.server 8000
```

Lalu buka browser dan akses:

```
http://localhost:8000
```

---

## 📁 Struktur Project

```
.
│── index.html         # Full UI + logic
│── README.md          # Dokumentasi
└── assets/            # (Opsional) ikon/cuaca
```

> Jika ingin dipisah menjadi `style.css` & `app.js`, saya bisa buatkan versi modular.

---

## 📸 Preview

<img width="1920" height="1200" alt="Screenshot 2025-12-01 231708" src="https://github.com/user-attachments/assets/2b7ec272-9da5-4aa7-9aed-8c046bae64dd" />


---

## 🤝 Kontribusi

Pull Request selalu terbuka untuk:

* Weather alert notification
* Fitur GPS auto-location
* Grafik trend temperatur (Chart)

---

## 📜 License

MIT – Bebas digunakan, dikembangkan, dan disebarluaskan.
