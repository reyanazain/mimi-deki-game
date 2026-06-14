CARA MEMASUKKAN GAMBAR (ART ASLI)
=================================
Simpan file PNG kamu ke folder ini dengan NAMA PERSIS seperti di bawah.
Latar HIJAU tidak perlu dihapus dulu — game otomatis menjadikannya transparan saat load.
File yang belum ada akan otomatis diganti placeholder, jadi game tetap bisa dimainkan.

mimi/        normal_idle.png  normal_walk.png  normal_jump.png
             power_idle.png   power_walk.png   power_jump.png
deki/        normal_idle.png  normal_walk.png  normal_jump.png
             power_idle.png   power_walk.png   power_jump.png
enemy/       spray_idle.png   spray_attack.png
items/       food1.png   food2.png   chicken.png
blocks/      bonus_box.png   ground.png   brick.png
goal/        flag_green.png  flag_red.png  house.png
bg/          neighborhood.png

KETERANGAN
- mimi/deki normal_*  = sprite versi RAMPING (state awal)
- mimi/deki power_*   = sprite versi GEMUK   (setelah makan paha ayam)
- enemy spray_idle    = semprotan diam ; spray_attack = sedang menyemprot
- items food1/food2   = 2 versi makanan kucing (koin), dipakai selang-seling
- items chicken       = paha ayam (power-up)
- blocks bonus_box    = kotak bonus (cap kaki) ; ground = tanah ; brick = bata
- goal flag_green     = bendera sebelum finish ; flag_red = setelah finish ; house = rumah (tujuan)
- bg neighborhood     = background kompleks perumahan

CARA MENJALANKAN GAME
- Jalankan server statis lalu buka index.html, contoh dari folder mimi-deki-game:
    python3 -m http.server 8000
  lalu buka  http://localhost:8000  di browser HP/desktop.
  (Membuka langsung file:// juga bisa, tapi chroma-key latar hijau hanya jalan via http server.)
