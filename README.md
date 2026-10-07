# Undangan Alpian & Nisa — One Piece

Paket siap unggah untuk akun `himakri-ui`, repository `alpian-nisa-one-piece`.
Repository belum dibuat dan situs belum diterbitkan oleh paket ini.

## Cara memasang

1. Buat repository baru bernama `alpian-nisa-one-piece` pada akun `himakri-ui`. Pilih Public jika menggunakan GitHub Free.
2. Ekstrak ZIP. Unggah isi folder ini langsung ke akar repository: `index.html`, `cover-preview.png`, `.nojekyll`, dan `README.md`. Jangan unggah ZIP atau menaruh semua file di dalam subfolder tambahan.
3. Buka Settings → Pages. Pada Build and deployment pilih Deploy from a branch, branch `main`, folder `/(root)`, lalu Save.
4. Tunggu sampai GitHub menampilkan situs sudah diterbitkan. Alamat yang direncanakan: https://himakri-ui.github.io/alpian-nisa-one-piece/
5. Pastikan alamat gambar https://himakri-ui.github.io/alpian-nisa-one-piece/cover-preview.png bisa dibuka, lalu bagikan alamat undangan di WhatsApp.

Jika memakai nama akun atau repository lain, ganti semua kemunculan `https://himakri-ui.github.io/alpian-nisa-one-piece/` di bagian `<head>` pada `index.html` sesuai alamat sebenarnya.

Metadata Open Graph sudah ada langsung dalam HTML. Sampul harus tetap menjadi file publik terpisah, bernama `cover-preview.png`. Tampilan pratinjau bergantung pada aplikasi penerima; aplikasi dapat menyimpan pratinjau lama dan tidak selalu memperbaruinya langsung.

Nama tamu: tambahkan `?to=Nama%20Tamu` pada URL undangan.

RSVP/ucapan masih berupa demo yang hanya tersimpan dalam browser pengunjung. Jawaban belum terkirim ke mempelai. Fitur tersebut membutuhkan layanan penyimpanan terpisah agar dapat menerima konfirmasi dari tamu.

Panduan resmi GitHub:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
