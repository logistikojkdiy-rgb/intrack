InTrack — Internship Tracker
Aplikasi web untuk manajemen operasional magang real-time. Memisahkan frontend statis dan backend serverless (Google Apps Script) menggunakan arsitektur iframe bridge asinkron demi menghindari kendala CORS dan latensi.

🌟 Fitur Utama
RBAC: Otorisasi berjenjang untuk Super Admin, Admin, Mentor, dan Intern.

Presensi Cerdas: Integrasi Geolocation API & Canvas API untuk selfie ber-watermark presisi.

Manajemen Alur Kerja: Pencatatan aktivitas, penugasan, pemantauan KPI, dan generate laporan PDF otomatis.

PWA (Progressive Web App): Mendukung instalasi standalone via Add to Home Screen.

💻 Stack & Arsitektur
Frontend: Vanilla HTML5/JS (ES6+) dan CSS sistem utilitas kustom.

Backend: Google Apps Script dengan basis data Google Sheets & Drive.

Komunikasi API: Promise-based wrapper (InTrackApi) via window.postMessage untuk eksekusi non-blocking.

🎨 Design Rationale (UI/UX)
Fokus pada aksesibilitas dan minimalisasi cognitive load:

Visual Feedback: Penggunaan palet warna semantik (Hijau: Sukses, Kuning: Pending, Merah: Ditolak) untuk umpan balik instan.

Mobile-First Layout: Transisi mulus ke Bottom Navigation Bar pada layar mobile untuk memastikan navigasi berada dalam zona nyaman ibu jari (Thumb Zone).

State Management: Penggunaan state loading asinkron untuk mencegah interaksi ganda dan kebingungan sistem.
