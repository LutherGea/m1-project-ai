-Elevator Pitch : 
    UMKM yang berjualan online sering menerima ulasan produk dari pelanggan. Namun, ulasan tersebut menumpuk dan sulit dianalisis secara manual. Proyek ini bertujuan membuat sistem analisis sentimen sederhana berbasis AI untuk mengklasifikasikan ulasan menjadi positif, negatif, atau netral, sehingga UMKM bisa cepat memahami kepuasan pelanggan.

-Problem Statement
    UMKM e-commerce lokal biasanya bergantung pada ulasan produk dari pelanggan untuk meningkatkan kualitas produk dan layanan. Sayangnya, proses membaca dan menganalisis ulasan secara manual membutuhkan waktu dan berisiko bias subjektif. Akibatnya, banyak masukan berharga dari pelanggan terlewat. Proyek ini akan membangun sistem sederhana berbasis AI yang mampu mengklasifikasikan ulasan pelanggan ke dalam kategori sentimen (positif, negatif, atau netral). Dengan solusi ini, UMKM dapat mengidentifikasi masalah lebih cepat, meningkatkan kualitas produk, dan menjaga loyalitas pelanggan.

-Scope
    1. In Scope
        -Analisis sentimen ulasan produk (positif, negatif, netral -Penggunaan dataset dummy singkat untuk eksplorasi awal.-Implementasi model
    2. Out of Scope
        -Analisis aspek lebih detail
        -Visualisasi dashboard

-Metrics
    -Akurasi minimal: ≥ 0.70.
    -F1-score target: ≥ 0.75.
    -Latensi prediksi: ≤ 1 detik per ulasan.

-Roadmap
    1. Minggu 1 (Inisialisasi & Perencanaan)
        -Menentukan problem statement (analisis sentimen ulasan produk UMKM).
        -Membuat struktur repository (data/, notebooks/, src/, docs/).-Menulis README awal + issue board.
        -Membuat dataset dummy (5–10 ulasan sederhana).

    2. Minggu 2 (Eksplorasi Data & Baseline)
        -Eksplorasi dataset dummy di notebook (tokenisasi teks, statistik sederhana).
        -Membuat baseline model menggunakan rule-based sederhana (contoh: kata positif/negatif).
        -Evaluasi baseline dengan metrik akurasi & F1-score.

    3. Minggu 3 (Model Machine Learning)
        -Mempersiapkan preprocessing teks (stopwords removal, TF-IDF).-Membangun model ML sederhana (Naive Bayes / Logistic Regression).
        -Melatih model pada dataset dummy dan evaluasi hasil.

    4. Minggu 4 (Peningkatan & Evaluasi)
        -Menambahkan dataset dummy tambahan (hingga 30–50 data) untuk variasi.
        -Bandingkan hasil model baseline vs model ML.
        -Dokumentasikan hasil eksperimen (akurasi, precision, recall, F1-score).

    5. Minggu 5 (Dokumentasi & Etika)
        -Menulis dokumentasi proyek di README (hasil, metrik, keterbatasan).
        -Menambahkan catatan risiko etika & privasi.
        -Menyusun presentasi singkat (1–2 slide).

    6. Minggu 6 (Finalisasi)
    -Review ulang code, repo, dan issue board.
    -Perbaikan berdasarkan feedback.
    -Finalisasi proyek untuk presentasi/ujian.

-Etika dan Privasi
    >Risiko: ulasan asli pelanggan dapat mengandung data pribadi (nama atau nomor kontak).
    >Mitigasi: gunakan dataset dummy pada tahap awal, anonimisasi data bila menggunakan ulasan nyata, dan hindari penyimpanan informasi sensitif.