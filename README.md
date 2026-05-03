# Tugas Praktikum 9 - Integrasi AI API

## Identitas

Nama  : Jana Rohman Wasiso  
NIM   : 123140046  
Kelas : PAM RB 

## Deskripsi

Pengembangan aplikasi **NotesApp**, yaitu aplikasi pencatat catatan berbasis Kotlin Multiplatform yang terintegrasi dengan **Gemini API** pada Praktikum 9.

Aplikasi ini digunakan untuk membantu pengguna membuat, merapikan, merangkum, dan mengembangkan catatan melalui fitur **AI Notes Assistant**. Pengguna dapat mengirim pesan atau instruksi melalui halaman chat, kemudian aplikasi mengirim prompt ke Gemini API dan menampilkan jawaban AI dalam bentuk percakapan.

Fitur AI menggunakan prompt yang dirancang khusus sebagai asisten catatan, dilengkapi dengan loading state, error handling, dan multi-turn conversation agar percakapan sebelumnya dapat digunakan sebagai konteks.

## Fitur Utama

- Mengintegrasikan **Gemini API** ke dalam aplikasi NotesApp
- Menggunakan model AI `gemini-2.5-flash`
- Menyediakan fitur **AI Notes Assistant** dalam bentuk chatbot
- Membantu pengguna membuat ide catatan
- Membantu pengguna merapikan isi catatan
- Membantu pengguna merangkum tulisan atau catatan
- Membantu pengguna membuat checklist dari instruksi singkat
- Membantu pengguna mengembangkan catatan menjadi lebih jelas dan terstruktur
- Menggunakan prompt yang dirancang khusus untuk asisten pencatat catatan
- Menampilkan percakapan dalam bentuk chat bubble
- Menampilkan loading indicator saat AI sedang memproses jawaban
- Menampilkan pesan error jika request AI gagal
- Menangani error seperti API key kosong, API key tidak valid, timeout, model tidak ditemukan, respons kosong, dan quota/rate limit
- Menonaktifkan tombol kirim ketika input kosong atau AI sedang loading
- Mendukung **multi-turn conversation** sehingga percakapan sebelumnya dapat digunakan sebagai konteks
- Menyediakan tombol **Clear** untuk menghapus percakapan

## Cara Menjalankan Aplikasi

1. Pilih Repository praktikump: https://github.com/10-046-JanaRohman/TugasPraktikum9_PAM_123140046.git 
2. Clone atau download repository ini.
3. Buka folder project menggunakan Android Studio.
4. Tunggu proses Gradle Sync sampai selesai.
5. Pilih emulator atau device Android.
6. Jalankan aplikasi dengan menekan tombol Run.
7. Aplikasi akan terbuka pada emulator atau device yang dipilih.

## Screenshoot Aplikasi
