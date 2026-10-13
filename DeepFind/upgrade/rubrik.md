# Rubrik penilaian

Skor = jumlah cek yang lulus dibagi 20. Lulus jika 18 atau lebih (90%). Setiap cek wajib menyertakan bukti (nama file, baris, atau kutipan). Tanpa bukti, cek dihitung gagal. Kerjakan cek mesin dengan pemeriksaan nyata, bukan opini.

## Cek mesin
1. AGENTS.md ada dan di bawah 24 KB.
2. Setiap SKILL.md punya frontmatter name dan description, dan name sama dengan nama foldernya.
3. Setiap SKILL.md di bawah 500 baris.
4. Semua file di references/ yang dirujuk SKILL.md benar-benar ada.
5. knowledge/INDEX.md, riwayat.md, evaluasi.md, dan catatan-pemakaian.md ada.
6. Isi _arsip_v4/ tidak berubah.
7. Semua butir di upgrade/kemampuan.md masih ada di file sistem.

## Cek perilaku (dari upgrade/tes/tes-tetap.md)
8. /search menulis kartu topik.
9. /search memakai sub-pertanyaan sesuai jenis topik.
10. Setiap klaim utama punya URL sumber.
11. Ada skor keyakinan dan pemisahan terbukti, dugaan kuat, spekulasi.
12. Data yang tidak ada ditulis "tidak ditemukan", bukan diperkirakan.
13. Nama, angka, dan tanggal tidak diringkas atau dibulatkan.
14. Pencarian berhenti sesuai kriteria dan batas kueri.
15. Celah ditandai dengan jelas.
16. Prompt Gemini memuat batasan, aturan data hilang, format, dan blok pelindung.
17. Hasil disimpan ke knowledge/riset/ dan INDEX.md diperbarui.
18. /cerna memuat peta pertanyaan dan jawaban yang lengkap.
19. /cerna tidak menambah fakta di luar hasil riset.
20. Jawaban kunci tes terpenuhi tanpa melanggar daftar terlarang.
