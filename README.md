Bank BNI
--------
Modul pembayaran Bank BNI untuk PrestaShop 1.6.x (branch: 1.6) dan PrestaShop 1.7.x (branch: master)

Modul ini dibuat berdasarkan modul BankWire/ps_wirepayment. Versi/perubahan akan selalu mengikuti modul tersebut.

Instalasi dan Konfigurasi
--------
* Download dari github ini (untuk PrestaShop 1.6.x ada di branch 1.6 dan untuk PrestaShop 1.7.x ada di branch master) atau dari website [Prestanesia][1].
* Rename Bankbni-master.zip menjadi Bankbni.zip
* Upload dari halaman Modules di BackOffice.
* Di halaman konfigurasi modul, masukan nama bank, no rekening, nama pemilik rekening dan lokasi/cabang bank.
* Modul akan membuat status order baru yaitu "Awaiting Bank BNI Payment"/"Menunggu pembayaran via Bank BNI".
* Untuk pengiriman email, modul menggunakan format email sendiri yang dapat Anda temukan di folder mails/bahasa-yang-digunakan/bankbni.html dan mails/bahasa-yang-digunakan/bankbni.txt.

Kustomisasi
--------
Tampilan saat konfirmasi dan pemilihan bank masih standar, jika akan disesuaikan dengan theme yang Anda gunakan silahkan override file .tpl terkait, sebagai referensi cara override file modul silahkan baca [Override default behaviour][2]


[1]: http://store.prestanesia.com
[2]: http://doc.prestashop.com/display/PS16/Overriding+default+behaviors

