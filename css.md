# 7 pertanyaan wawancara CSS

1. **Apa itu Model Kotak (_Box Model_)?** Ia mendefinisikan struktur sebuah elemen, terdiri dari (mulai dari dalam ke luar): _Content_, _Padding_, _Border_, dan _Margin_.
2. **Jelaskan `box-sizing: border-box`.** Ia memaksa tinggi dan lebar elemen termasuk _padding_ dan _border_, bukannya memperluas elemen ke luar.
3. **Apa itu hierarki spesifisitas CSS?** Gaya sebaris (1000) > ID (100) > Kelas/Atribute/Kelas pseudo (10) > Elemen/elemen-pseudo (1).
4. **Kapan anda harus menggunakan `!important`?** Hanya sebagai pilihan terakhir, untuk menimpa gaya sebaris atau pustaka gaya pihak ketiga yang tak bisa diubah.
5. **Apa itu Marjin yang Menciut (_Margin Collapsing_)?** Saat marjin vertikal sebuah elemen blok bersisian bertemu, mereka bergabung menjadi marjin tunggal sama besar dengan nilai yang paling besar diantara keduanya.
6. **Apa itu _Stacking Context_?** Konseptualisasi 3 dimensi dari elemen-elemen dalam sumbu Z. Ia bisa dipicu oleh properti seperti `position`(dengan _z-index_), `opacity < 1`, dan `transform`.
7. **Perbedaan antara `display:none` dan `visibility: hidden`?** `none` mengeluarkan elemen sepenuhnya dari alur dokumen. Sementara `hidden` hanya membuatnya tersembunyi tapi tetap mempertahankan ruang fisiknya.
