# Rangkuman Materi Peluang

## 1. Dasar-dasar peluang

### Deskripsi

- **Percobaan** adalah tindakan atau kegiatan yang dapat diulang dalam keadaan yang sama untuk memperoleh hasil tertentu.
- **Ruang sampel** adalah himpunan semua hasil yang mungkin dari suatu percobaan. Notasi: `S`.
- **Titik sampel** adalah anggota ruang sampel.
- **Kejadian** adalah himpunan bagian dari ruang sampel.
- **Kejadian sederhana** memiliki satu titik sampel.
- **Kejadian majemuk** memiliki lebih dari satu titik sampel.

### Rumus

Bagian ini berisi istilah dasar; belum ada rumus khusus.

### Contoh

Pada pelemparan dadu, `S = {1, 2, 3, 4, 5, 6}` adalah ruang sampel. Kejadian muncul angka 1 adalah kejadian sederhana `{1}`, sedangkan kejadian muncul angka genap `{2, 4, 6}` adalah kejadian majemuk.

## 2. Peluang suatu kejadian

### Deskripsi

Peluang kejadian menyatakan besar kemungkinan suatu kejadian terjadi. Jika semua hasil dalam ruang sampel memiliki peluang yang sama, maka:

### Rumus

\[
P(A) = \frac{n(A)}{n(S)}
\]

`n(A)` adalah banyak anggota kejadian `A`, sedangkan `n(S)` adalah banyak anggota ruang sampel.

### Contoh: melempar dadu

Sebuah dadu bernomor 1 sampai 6 dilempar. Ruang sampelnya:

`S = {1, 2, 3, 4, 5, 6}`, sehingga `n(S) = 6`.

Untuk kejadian muncul angka 1, `A = {1}` dan `n(A) = 1`. Jadi:

`P(A) = n(A) / n(S) = 1/6`

## 3. Peluang komplemen

### Deskripsi

Komplemen kejadian `A`, ditulis `Aᶜ`, adalah kejadian bahwa `A` tidak terjadi.

### Rumus

\[
P(A^c) = 1 - P(A)
\]

### Contoh: komplemen munculnya bilangan ganjil

Pada pelemparan dadu, misalkan `A` adalah kejadian munculnya bilangan ganjil, yaitu `{1, 3, 5}`. Komplemennya adalah munculnya bilangan genap:

`Aᶜ = {2, 4, 6}`, sehingga `n(Aᶜ) = 3`.

\[
P(A^c) = \frac{3}{6} = \frac{1}{2}
\]

## 4. Kejadian saling bebas (stokastik)

### Deskripsi

Dua kejadian saling bebas jika terjadinya satu kejadian tidak memengaruhi peluang kejadian yang lain.

### Rumus

\[
P(A \cap B) = P(A) \times P(B)
\]

### Contoh: lulus dua ujian

Seorang siswa mengikuti ujian Matematika dan Bahasa Inggris. Peluang lulus Matematika adalah `0,8`, sedangkan peluang lulus Bahasa Inggris adalah `0,7`. Hasil kedua ujian tidak saling memengaruhi.

- `A`: lulus Matematika
- `B`: lulus Bahasa Inggris

\[
P(A \cap B) = 0{,}8 \times 0{,}7 = 0{,}56
\]

Jadi, peluang siswa lulus kedua ujian adalah **0,56**.

## 5. Peluang bersyarat

### Deskripsi

Peluang bersyarat menghitung peluang `B` terjadi dengan syarat `A` telah terjadi. Rumus berlaku untuk `P(A) > 0`.

### Rumus

\[
P(B \mid A) = \frac{P(A \cap B)}{P(A)}
\]

### Contoh: diabetes dan hipertensi

Sebuah klinik mencatat peluang seorang pasien menderita diabetes sebesar `0,10` dan peluang pasien menderita diabetes sekaligus hipertensi sebesar `0,06`. Peluang pasien menderita hipertensi jika diketahui menderita diabetes adalah:

- `A`: pasien menderita diabetes
- `B`: pasien menderita hipertensi

\[
P(B \mid A) = \frac{0{,}06}{0{,}10} = 0{,}6
\]

Jadi, peluang bersyarat tersebut adalah **0,6**.

## 6. Kejadian saling lepas

### Deskripsi

Dua kejadian saling lepas jika keduanya tidak dapat terjadi pada saat yang sama. Keduanya tidak memiliki titik sampel yang sama.

### Rumus

\[
A \cap B = \varnothing \quad\text{atau}\quad n(A \cap B) = 0
\]

Untuk kejadian saling lepas, `A ∩ B = ∅`, sehingga peluang gabungannya:

\[
P(A \cup B) = P(A) + P(B)
\]

### Contoh

Pada pelemparan satu dadu, misalkan `A = {1}` (muncul angka 1) dan `B = {2}` (muncul angka 2). Kedua kejadian saling lepas karena tidak dapat muncul bersamaan. Maka `P(A ∪ B) = 1/6 + 1/6 = 1/3`.

**Diagram pada sumber:** dalam ruang sampel `S`, lingkaran `A` dan `B` terpisah dan tidak beririsan.

## 7. Kejadian tidak saling lepas

### Deskripsi

Dua kejadian tidak saling lepas jika keduanya dapat terjadi pada saat yang sama. Keduanya memiliki titik sampel yang sama.

### Rumus

\[
A \cap B \ne \varnothing \quad\text{atau}\quad n(A \cap B) \ne 0
\]

\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]

Irisan `P(A ∩ B)` dikurangkan agar bagian yang terhitung dua kali hanya dihitung satu kali.

### Contoh

Pada pelemparan satu dadu, misalkan `A = {2, 4, 6}` (muncul angka genap) dan `B = {4, 5, 6}` (muncul angka lebih dari 3). Irisannya `A ∩ B = {4, 6}`. Maka `P(A ∪ B) = 3/6 + 3/6 - 2/6 = 4/6 = 2/3`.

**Diagram pada sumber:** dalam ruang sampel `S`, lingkaran `A` dan `B` beririsan.
