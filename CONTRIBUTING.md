# Panduan Kontribusi Tim - Layanan Antrean Kampus

## Anggota Tim
| Nama | NIM | GitHub | Peran |
| :--- | :--- | :--- | :--- |
| Anisa | 240131135 | annisaaa56-ops | Ketua Tim / Admin |
| Akhmad Yuda Prawira | 240131009 | Poligonxm512 | Anggota |
| Dessy Adellia | 240131017 | dessyadell043-del | Anggota |
| Emilda Sari | 240131144 | emildasari7124-oss | Anggota |
| Rizki Faulina Wati | 240131109 | rizkyfaulinawati-dev | Anggota |

## Alur Kerja di Termius / VPS
Semua anggota bekerja lewat Termius (VPS), bukan lewat web GitHub.
1. Buka Termius, login ke VPS.
2. Masuk ke folder proyek: `cd ~/proyek/antrean-kampus`
3. Update dulu: `git pull origin main`
4. Buat branch baru, jangan kerja di `main`.

## Strategi Branching - GitHub Flow
- `main`: branch utama, harus selalu stabil & sudah di-review.
- Format branch: `tipe/nama-tugas-nama`
- Contoh: `docs/profil-anisa`, `feat/form-antrean-yuda`

## Tugas Ketua Tim / Admin (Anisa)
- Mengatur repository (Public, Branch Protection, Settings).
- Me-review dan memberi 1 approval di setiap Pull Request.
- Yang boleh Merge ke `main` hanya Ketua Tim.
- Mengecek hasil kerja anggota lewat Termius / VPS sebelum merge.

## Tugas Anggota
- Kerja di branch sendiri lewat Termius / VPS.
- Wajib `git pull` dulu biar tidak konflik.
- Wajib buat Pull Request setelah selesai.

## Conventional Commits
Format: `tipe: deskripsi singkat`
- `feat:` fitur baru, `fix:` perbaikan bug, `docs:` dokumentasi
- Contoh: `docs: tambah profil anisa`

## Aturan Pull Request (PR)
1. Wajib lewat Pull Request, DILARANG push langsung ke `main`.
2. Wajib 1 approval dari Ketua Tim (Anisa).
3. Wajib isi judul & deskripsi PR dengan jelas.

## Larangan
- Dilarang menyimpan rahasia (password, token, API key) di repository.
- Dilarang commit file `.env` atau data pribadi.
- Dilarang mengubah setting repository tanpa izin Ketua Tim.

