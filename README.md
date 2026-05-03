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

- Input Expense
<img width="430" height="868" alt="Screenshot 2026-05-03 232511" src="https://github.com/user-attachments/assets/c3f72002-9a6b-443e-9dff-43d77642b99b" />

- Expense Summary 
<img width="456" height="865" alt="Screenshot 2026-05-03 232433" src="https://github.com/user-attachments/assets/e64643ba-c949-4d1b-a139-465c3483dbc1" />

- Loading State
<img width="429" height="871" alt="Screenshot 2026-05-03 232156" src="https://github.com/user-attachments/assets/bdc767c4-edd7-491a-b086-edd6fcebafe5" />

- Ai Analysis
<img width="460" height="869" alt="Screenshot 2026-05-03 232219" src="https://github.com/user-attachments/assets/46aecd44-4bc3-46cb-bfbf-47994ea1c200" />

- Error Handling
<img width="428" height="883" alt="Screenshot 2026-05-03 232634" src="https://github.com/user-attachments/assets/7817493b-8e68-45ea-ba01-a53ccd787043" />





