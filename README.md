# Penerjemah-Bahasa-Offline
Library kecil-kecilan buat kamu yang mau bikin aplikasi java/android penerjemah offline.

## fitur:
### 1. penerjemahan secara offline
Terjemahkan teks tanpa koneksi internet/jaringan apapun.
### 2. Ringan dan kecil
Sangat ringan dioprasikan dan berukuran kecil (tidak sampai 10kB).
### 3. Mampu menerjemahkan teks yang sangat panjang
Tidak ada batasan terpanjang untuk teks yang ingin diterjemahkan (kembali ke kemampuan / spesufikasi perangkat anda).
### 4. Terjemah satu klik
Terjemah satu kata / kalimat / paragraf / artikel / dokumen dalam sekali klik.
### 5. Bukan API Google Translate
Ini adalah library buatan sendiri yang dibuat dari nol.
## Cara pakai
Main class library ini ada di
##### id.kaliagung.translator.Translator.java
Ada beberapa method yang mudah kamu gunakan. Seperti:
####### load()
Digunakan untuk memuat kamus yang ingin digunakan, misal kamus jawa, sunda, bali, dll.
Struktur kamus seperti pasangan kata dalam dua bahasa, misal:
ada:ana;
manis:legi;
dalam:jero;
####### translateTo()
