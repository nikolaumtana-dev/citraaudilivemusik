# ArSonMix — Mixer Live (PWA)

Isi paket: index.html, manifest.json, sw.js, icon-192.png, icon-512.png

## Cara pasang di GitHub Pages
1. Buat repositori baru di GitHub (misal: `arsonmix-app`), set Public.
2. Unggah KELIMA file di atas ke root repositori (Add file > Upload files).
3. Buka Settings > Pages > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1-2 menit. Alamatnya: https://NAMA-GITHUB-ANDA.github.io/arsonmix-app/

## Pasang di HP
- Android: buka alamat di Chrome > menu ⋮ > "Install app" / "Add to Home screen".
- iPhone: buka di Safari > tombol Bagikan > "Add to Home Screen".
Setelah terbuka sekali dengan internet, aplikasi bisa dipakai offline.

## Sebelum acara
1. Buka aplikasi, ketuk layar sekali, lalu masuk tab SETUP > "Izinkan mikrofon".
2. Pilih input tiap channel (mic, interface USB OTG, atau File musik).
3. Putar HP ke landscape. Tombol ☰ membuka sidebar (preset dan snapshot).
4. Uji dengan "Tes nada" di tab SIGNAL CHECK dan cek latensi dengan headphone.
5. Sambungkan HP ke charger. Layar dijaga tetap menyala selama dipakai.

## Memperbarui versi
Ganti index.html di repositori, lalu ubah angka versi di sw.js (V='arsonmix-v2' menjadi v3, dst) agar HP memuat versi baru.

## Catatan
- Di layar HP yang pendek, baris FX di strip disembunyikan; atur FX lewat tab FX RACK.
- Plugin VST3 tidak bisa dimuat; efek bawaan dipakai.
- Latensi audio browser di HP lebih tinggi daripada aplikasi native.
