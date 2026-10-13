# DeepFind: cara pakai

DeepFind mencari dan mengumpulkan informasi tentang topik apa pun. Ada empat perintah. Ketik di kotak chat project DeepFind.

| Perintah | Fungsi | Contoh |
|---|---|---|
| /search [topik] | Mencari sampai menemukan informasi paling berharga, menyimpannya, dan menandai celah | /search dampak AI terhadap lapangan kerja di Indonesia 2026 |
| /gemini-prompt | Menyusun prompt Gemini Deep Research untuk celah yang masih ada | /gemini-prompt untuk celah regulasi data pribadi |
| /cerna | Menjelaskan hasil atau topik secara lengkap dan mudah dipahami | /cerna hasil search tadi |
| /upgrade | Memperbaiki sistem DeepFind berdasarkan masalah yang terukur. Menunggu persetujuan Anda | /upgrade |

## Alur yang biasa
1. /search topik. Agen mencari sendiri dulu.
2. Jika ada celah penting, agen memberi prompt Gemini. Jalankan di Gemini: Tools, Deep Research, tempel prompt, periksa rencana lewat Edit plan, lalu Start research.
3. Tempel hasil Gemini ke chat. Agen memeriksa sitasi dan menyimpannya.
4. /cerna untuk memahami hasilnya.

## Peta folder
- AGENTS.md: aturan inti, selalu aktif.
- .agents/skills/: isi keempat perintah.
- knowledge/: memori (INDEX.md, riwayat, evaluasi, catatan pemakaian, hasil riset).
- upgrade/: tes tetap, rubrik, daftar kemampuan, kartu masalah, usulan.
- _arsip_v4/: versi lama, tidak dipakai.

## Tips
- Satu percakapan untuk satu tugas. Memori ada di folder knowledge, bukan di riwayat chat.
- Setelah /search, beri nilai 1 sampai 5 di knowledge/catatan-pemakaian.md pada kolom nilai pengguna. Itu bahan /upgrade.
