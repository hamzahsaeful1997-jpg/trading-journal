# One Percent Trading Journal — Android v1.0

## Instalasi Android
Aplikasi ini adalah PWA offline-first. Agar bisa dipasang dan service worker aktif:
1. Upload semua file dalam folder ini ke hosting static HTTPS (contoh GitHub Pages atau Netlify).
2. Buka URL HTTPS tersebut melalui Chrome Android.
3. Pilih menu browser **Install app** atau **Add to Home screen**.
4. Setelah dipasang, buka dari ikon layar utama.

## Fitur
- Dashboard net P/L, total transaksi, win rate, profit factor, max drawdown, equity curve.
- Trade log tambah/edit/hapus, pencarian dan filter.
- Kalender profit/loss bulanan.
- Analytics average win/loss, expectancy, best trade, pair, BUY/SELL, risk, loss streak, average R.
- Local Insight Engine untuk evaluasi statistik, performa strategi, drawdown, dan kebiasaan jurnal.
- Backup/restore JSON dan export CSV.
- IndexedDB lokal dan cache offline.

## Catatan
Insight v1 adalah mesin evaluasi statistik berbasis aturan, bukan LLM generatif dan bukan prediksi pasar. Semua P/L diinput manual. Data berada di browser/perangkat; backup JSON secara berkala. Belum ada cloud sync, integrasi MT4/MT5, OCR screenshot, atau eksekusi order.
