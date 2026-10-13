# Templat prompt Gemini untuk /upgrade (kontrak solusi)

Gunakan bersama skill gemini-prompt. Isi semua bagian dengan data nyata dari kartu masalah.

<masalah>
[GEJALA MENTAH + SKOR TES SEKARANG + TARGET]
</masalah>
<batasan>
[FILE YANG BOLEH DIUBAH, BATAS UKURAN (SKILL.md di bawah 500 baris, AGENTS.md di bawah 24 KB), LINGKUNGAN ANTIGRAVITY YANG SUDAH TERVERIFIKASI]
</batasan>
<sudah_dicoba>
[DAFTAR YANG GAGAL. JANGAN DIUSULKAN LAGI]
</sudah_dicoba>
<permintaan>
Berikan 2 sampai 3 kandidat solusi untuk masalah di atas. DILARANG menjelaskan latar belakang, definisi, atau sejarah. Setiap kandidat wajib memuat:
1. Mekanisme: mengapa ini mengatasi akar masalah.
2. Bukti: kasus nyata sistem sejenis dengan hasil terukur (sumber dan tanggal). Opini tidak dihitung.
3. Implementasi: teks atau perubahan persis pada file mana.
4. Dampak yang diharapkan pada tes yang gagal, dan cara memverifikasinya.
5. Risiko dan hal yang bisa memperburuk.
Jika tidak ada solusi dengan bukti, tulis "tidak ditemukan solusi terbukti" dan sebutkan di mana kamu sudah mencari. Jangan mengarang.
Akhiri dengan tabel penelusuran: setiap rekomendasi dipetakan ke gejala di bagian masalah. Rekomendasi tanpa gejala dihapus.
</permintaan>

Tambahkan blok dari .agents/skills/gemini-prompt/references/blok-pelindung.md di akhir.
