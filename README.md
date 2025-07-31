# ValeSafe - Memory Safety Toolkit in Vale
> "Karena pointer yang salah bisa bikin server meledak 💥"

Memory Safety Audit Framework in Vale ─ Mendeteksi akses memory tidak valid (buffer overflows, use-after-free) 

**ValeSafe** toolkit berbasis pemrograman [Vale](https://vale.dev) yang dirancang untuk membantu para pengembang dalam menganalisis, melindungi, dan memantau akses memori secara aman. Proyek ini menekankan pada **keamanan memori** (memory safety) melalui fitur-fitur seperti static analysis, custom allocator, reference tracing, dan simulasi kerentanan seperti use-after-free.

## V/M
- Membantu mendeteksi kerentanan memori seperti buffer overflow, UAF, dan akses ilegal
- Memberikan alat bantu analisis statis dan dinamis bagi developer low-level atau reverse engineer
- Menyediakan alokasi memori yang aman dan transparan
- Menyediakan CLI sederhana untuk menjalankan berbagai fitur secara langsung

## Feats

| Fitur                  | Deskripsi Singkat |
|------------------------|-------------------|
| Static Analyzer      | Menganalisis source code untuk mendeteksi pola akses memori yang berbahaya |
| Safe Allocator       | Fungsi alokasi dan dealokasi memori dengan perlindungan dan statistik internal |
| Memory Access Logger | Logging real-time saat terjadi akses baca/tulis ke alamat memori |
| Reference Tracing     | Melacak referensi dan lifetime pointer dengan transparansi |
| Guarded Memory Block | Proteksi tambahan pada blok memori menggunakan nilai "canary" |
| CLI Interaktif        | Antarmuka terminal sederhana untuk menjalankan berbagai fungsi ValeSafe |

### Contributors/VND
- PwnOsec Research & ZDG Asian Development
