📧 Auto-Responder Email Workflow with n8n
Projek ini adalah bagian dari tugas Implementasi AI untuk Pemasaran. Workflow ini dirancang untuk mengotomatiskan proses pengiriman email konfirmasi pendaftaran segera setelah pengguna mengisi formulir pendaftaran.

🚀 Fitur Utama
- n8n Form Trigger: Menangkap input Nama, Email, dan pilihan Kelas secara langsung.
- Dynamic Personalization: Menggunakan variabel dinamis untuk menyapa pendaftar secara personal di dalam email.
- Professional HTML Template: Email dikirim dalam format HTML yang responsif dan rapi.
- Automated Delivery: Terintegrasi langsung dengan Gmail API untuk pengiriman instan.

🛠️ Teknologi yang Digunakan
- n8n Self-Host: Sebagai platform orchestrator otomatisasi.
- Gmail API: Untuk layanan pengiriman email.
- HTML & CSS: Untuk mendesain template bodi email.

📂 Struktur File
- Auto_Responder_Email.json: File export workflow yang dapat di-import langsung ke n8n.
- README.md: Dokumentasi projek.

📝 Cara Penggunaan
1. Import file .json ke dalam instance n8n Anda.
2. Konfigurasikan Gmail Credential menggunakan OAuth2 di n8n.
3. Aktifkan workflow (set to Active).
4. Gunakan Production URL dari node n8n Form untuk mulai menerima pendaftaran.
