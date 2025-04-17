# Tugas-CF-Fuzzy_Logic

Certainty Factor adalah metode yang digunakan untuk menangani ketidakpastian dalam sistem pakar. CF mengukur tingkat keyakinan seorang pakar terhadap sebuah kesimpulan berdasarkan gejala yang diberikan.
- CF bernilai antara -1 hingga +1:
- +1, sangat yakin bahwa atau netral
- -1, sangat yakin bahwa fakta salah

CF menggabungkan berbagai gejala dengan bobot keyakinan berbeda, memberikan hasil akhir diagnosis yang proporsional. Perhitungan dilakukan menggunakan rumus gabungan CF:
                      CFgabungan = CF1 + CF2.(1-CF1)
Dalam studi kasus yang kamu kerjakan, sistem pakar berhasil menentukan diagnosis flu berdasarkan input gejala dan memberikan hasil berupa tingkat keyakinan numerik (misalnya 0.97).

Fuzzy Logic adalah metode logika yang menangani nilai-nilai yang tidak pasti atau ambigu. Tidak seperti logika klasik (hanya 0 atau 1), fuzzy logic menggunakan derajat keanggotaan antara 0 dan 1.
Cocok untuk kasus seperti "suhu tinggi", "lembab", "sedang", yang tidak bisa dikategorikan secara tegas.
Komponen utama:
- Fuzzy set: himpunan kabur
- Membership function: fungsi keanggotaan (misal: suhu 28°C bisa 0.6 "nyaman", 0.4 "panas")
- Fuzzification: ubah nilai numerik ke fuzzy
- Inference (aturan IF-THEN): logika fuzzy
- Defuzzification: hasil fuzzy ke nilai numerik (misalnya: kipas 66%)
Dalam studi kasus kamu (pengaturan kipas AC), sistem dapat menentukan kecepatan kipas berdasarkan suhu dan kelembaban menggunakan aturan fuzzy yang kamu buat sendiri.


​
 
