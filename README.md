# EduTrack AI 🎓🤖

> **Smart Academic Task Extractor & Productivity Manager for Students**

EduTrack AI adalah aplikasi manajemen tugas akademis berbasis *mobile* yang memanfaatkan kecerdasan buatan (*Generative AI*) untuk mengekstrak pengumuman tugas perkuliahan mentah dari dosen atau grup obrolan menjadi jadwal, pengingat, dan kalender terstruktur secara otomatis.

---

## 🚀 Fitur Utama

- 🤖 **Smart AI Task Extractor:** Mengekstrak informasi tenggat waktu, mata kuliah, dan rincian tugas secara otomatis dari teks pengumuman menggunakan Google Gemini API.
- 📅 **Interactive Academic Calendar:** Visualisasi tenggat waktu pengerjaan tugas harian dan mingguan dalam tampilan kalender intuitif.
- ⚡ **Real-Time Task Sync:** Pengelolaan status tugas (*To-Do*, *In Progress*, *Done*) yang tersinkronisasi secara langsung menggunakan Firebase Firestore.
- 🔐 **Seamless Authentication:** Akses akun yang aman menggunakan Firebase Authentication (Email/Password & Google Sign-In).

---

## 🛠️ Tech Stack & Modul Sistem

- **Frontend / Mobile UI:** [Flutter](https://flutter.dev/) (Dart) & `flutter_bloc` / `provider`
- **Backend & Database:** [Firebase Firestore](https://firebase.google.com/) & Firebase Auth
- **AI Engine:** [Google Gemini API](https://ai.google.dev/) (`google_generative_ai`)
- **State Management:** Provider / BLoC
- **Calendar & UI Components:** `table_calendar`, `intl`

---

## 👥 Tim Pengembang (3 คน / Roles)

| Peran | Anggota Tim | Focus Modul |
|---|---|---|
| **Frontend Lead** | @username1 | UI/UX Design, Navigation, Dashboard, & Calendar Screen |
| **Backend Lead** | @username2 | Firebase Auth, Firestore Data Schema, & Security Rules |
| **AI Integration Lead** | @username3 | Gemini API Prompting, JSON Parsing, & State Integration |

---

## 💻 Panduan Instalasi & Setup Lokal

### 1. Prasyarat (*Prerequisites*)
Pastikan perangkat kamu sudah terinstall:
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (versi >= 3.x.x)
- Git
- VS Code / Android Studio

### 2. Clone Repositori
```bash
git clone [https://github.com/username-kamu/edutrack-ai.git](https://github.com/username-kamu/edutrack-ai.git)
cd edutrack-ai