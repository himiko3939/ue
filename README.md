
# UEEx Miner Bot

Register : https://t.me/UEEx_Miner_bot/UEB_Miner_Bot?startapp=kBNoWEHfEAAwUWr8woh


## Installation

1. **Download Python 3.12+**
   - Pastikan kamu sudah memiliki Python versi 3.10 atau yang lebih baru. Kamu bisa mendownloadnya dari [python.org](https://www.python.org/downloads/).

2. **Install Module**
   - Buka command prompt atau terminal, lalu jalankan perintah:
     ```
     pip install requests colorama
     ```
   - Ini akan menginstal dua modul yang diperlukan: `requests` untuk melakukan permintaan HTTP dan `colorama` untuk memberi warna teks di konsol.

3. **Buka Bot UECoin di PC (Telegram Web / Desktop)**
   - Buka Telegram Web atau Telegram Desktop di PC kamu.

4. **Ambil Query**
   - Buka Bot UECoin dan lakukan inspeksi elemen di halaman tersebut.
   - Pergi ke tab Application (biasanya di browser, ada di bagian atas inspector).
   - Pilih `session storage` dan kemudian `ueex-mining-be9.pages.dev`.
   - Di dalamnya, cari `__telegram_initparam` dan temukan `tgwebappdata`.
   - Ambil nilai `query_id=xxx` atau `user=xxx` (ambil semua nilai ini kecuali `tgwebappnya`).

5. **Paste di query.txt**
   - Buat atau buka file `query.txt` dan paste nilai `query_id` atau `user=xxx` yang telah kamu ambil sebelumnya.
  
## Features
- Auto Claim
- Auto Refresh Token
- Multi Account